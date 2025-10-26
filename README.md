# ldcheck

# Clone
    git clone https://github.com/MrFluffyOven/ldcheck.git
# ldcheck all
    python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib:$OUT/recovery/root/system/lib/hw:$OUT/recovery/root/vendor/lib:$OUT/recovery/root/vendor/lib/hw -d $OUT/recovery/root/vendor/bin/*; python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib:$OUT/recovery/root/system/lib/hw:$OUT/recovery/root/vendor/lib:$OUT/recovery/root/vendor/lib/hw -d $OUT/recovery/root/vendor/bin/hw/*; python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib:$OUT/recovery/root/system/lib/hw:$OUT/recovery/root/vendor/lib:$OUT/recovery/root/vendor/lib/hw -d $OUT/recovery/root/vendor/lib/*; python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib:$OUT/recovery/root/system/lib/hw:$OUT/recovery/root/vendor/lib:$OUT/recovery/root/vendor/lib/hw -d $OUT/recovery/root/system//bin/*
