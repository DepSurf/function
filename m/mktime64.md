# Function: <code>mktime64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eabe0)
Location: kernel/time/time.c:326
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - arch/x86/platform/efi/efi.c:efi_get_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/rtc-lib.c:rtc_tm_to_time64
```
**Symbols:**

```
ffffffff810eabe0-ffffffff810eac77: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1880)
Location: kernel/time/time.c:333
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/rtc-lib.c:rtc_tm_to_time64
```
**Symbols:**

```
ffffffff810f1880-ffffffff810f1917: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f8a00)
Location: kernel/time/time.c:333
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/rtc-lib.c:rtc_tm_to_time64
```
**Symbols:**

```
ffffffff810f8a00-ffffffff810f8a97: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810faa20)
Location: kernel/time/time.c:423
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/rtc-lib.c:rtc_tm_to_time64
```
**Symbols:**

```
ffffffff810faa20-ffffffff810faab7: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811053b0)
Location: kernel/time/time.c:389
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/rtc-lib.c:rtc_tm_to_time64
```
**Symbols:**

```
ffffffff811053b0-ffffffff81105447: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811101c0)
Location: kernel/time/time.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/rtc-lib.c:rtc_tm_to_time64
```
**Symbols:**

```
ffffffff811101c0-ffffffff8111025f: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111b800)
Location: kernel/time/time.c:365
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_time64
  - drivers/rtc/class.c:__rtc_register_device
```
**Symbols:**

```
ffffffff8111b800-ffffffff8111b89f: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126230)
Location: kernel/time/time.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_time64
```
**Symbols:**

```
ffffffff81126230-ffffffff811262c8: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811321d0)
Location: kernel/time/time.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_time64
```
**Symbols:**

```
ffffffff811321d0-ffffffff81132268: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81141640)
Location: kernel/time/time.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/class.c:rtc_device_get_offset
```
**Symbols:**

```
ffffffff81141640-ffffffff811416d8: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113d850)
Location: kernel/time/time.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/class.c:rtc_device_get_offset
```
**Symbols:**

```
ffffffff8113d850-ffffffff8113d8e8: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113eaa0)
Location: kernel/time/time.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff8113eaa0-ffffffff8113eb34: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81161f30)
Location: kernel/time/time.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff81161f30-ffffffff81161fc4: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81194e50)
Location: kernel/time/time.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff81194e50-ffffffff81194efc: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d2b90)
Location: kernel/time/time.c:431
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff811d2b90-ffffffff811d2c3c: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e6e80)
Location: kernel/time/time.c:431
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff811e6e80-ffffffff811e6f2c: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fcbd0)
Location: kernel/time/time.c:449
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff811fcbd0-ffffffff811fcc7c: mktime64 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff800010199b88)
Location: kernel/time/time.c:433
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_time64
```
**Symbols:**

```
ffff800010199b88-ffff800010199c60: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4574)
Location: kernel/time/time.c:433
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_time64
```
**Symbols:**

```
c03e4574-c03e4690: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001f9e80)
Location: kernel/time/time.c:433
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtas-rtc.c:rtas_get_boot_time
  - arch/powerpc/kernel/rtas-proc.c:ppc_rtas_clock_show
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_time64
```
**Symbols:**

```
c0000000001f9e80-c0000000001f9f28: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a0c2)
Location: kernel/time/time.c:433
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_time64
```
**Symbols:**

```
ffffffe00012a0c2-ffffffe00012a18c: mktime64 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112a980)
Location: kernel/time/time.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_time64
```
**Symbols:**

```
ffffffff8112a980-ffffffff8112aa18: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d1f0)
Location: kernel/time/time.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_time64
```
**Symbols:**

```
ffffffff8111d1f0-ffffffff8111d288: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811286a0)
Location: kernel/time/time.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_time64
```
**Symbols:**

```
ffffffff811286a0-ffffffff81128738: mktime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
time64_t mktime64(const unsigned int year0, const unsigned int mon0, const unsigned int day, const unsigned int hour, const unsigned int min, const unsigned int sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81134d20)
Location: kernel/time/time.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_decode_time
  - drivers/rtc/lib.c:rtc_tm_to_time64
```
**Symbols:**

```
ffffffff81134d20-ffffffff81134db8: mktime64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
