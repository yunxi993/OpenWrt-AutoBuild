diff --git a/utils/xfsprogs/Makefile b/utils/xfsprogs/Makefile
index 77cb5806..69021034 100644
--- a/utils/xfsprogs/Makefile
+++ b/utils/xfsprogs/Makefile
@@ -67,7 +67,7 @@ CONFIGURE_ARGS += \
		--disable-scrub \
		--disable-libicu

-TARGET_CFLAGS += -DHAVE_MAP_SYNC
+TARGET_CFLAGS += -DHAVE_MAP_SYNC -D_LARGEFILE64_SOURCE
TARGET_LDFLAGS += $(if $(CONFIG_USE_GLIBC),-lrt)
