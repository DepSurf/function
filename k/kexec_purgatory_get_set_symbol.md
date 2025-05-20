# Function: <code>kexec_purgatory_get_set_symbol</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8110efe0)
Location: kernel/kexec_file.c:1012
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8110efe0-ffffffff8110f0c6: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81116690)
Location: kernel/kexec_file.c:968
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff81116690-ffffffff81116776: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8111ddd0)
Location: kernel/kexec_file.c:993
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8111ddd0-ffffffff8111deb6: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8111f990)
Location: kernel/kexec_file.c:994
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8111f990-ffffffff8111fa76: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8112b130)
Location: kernel/kexec_file.c:996
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8112b130-ffffffff8112b216: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:1024
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff8113a2fe-ffffffff8113a348: kexec_purgatory_get_set_symbol.cold.9 (STB_LOCAL)
ffffffff811395c0-ffffffff81139663: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:1082
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff81145bce-ffffffff81145c18: kexec_purgatory_get_set_symbol.cold.10 (STB_LOCAL)
ffffffff81144e90-ffffffff81144f33: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:1127
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff81150f8c-ffffffff81150fd8: kexec_purgatory_get_set_symbol.cold (STB_LOCAL)
ffffffff81150290-ffffffff8115033a: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:1132
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff8115cc04-ffffffff8115cc50: kexec_purgatory_get_set_symbol.cold (STB_LOCAL)
ffffffff8115bf20-ffffffff8115bfca: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:1119
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff8116d930-ffffffff8116d97c: kexec_purgatory_get_set_symbol.cold (STB_LOCAL)
ffffffff8116ce80-ffffffff8116cf2a: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:1137
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff81be4666-ffffffff81be46b2: kexec_purgatory_get_set_symbol.cold (STB_LOCAL)
ffffffff81169500-ffffffff811695aa: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:1139
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff81bd6487-ffffffff81bd64d3: kexec_purgatory_get_set_symbol.cold (STB_LOCAL)
ffffffff8116a230-ffffffff8116a2da: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:1139
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff81cb2d74-ffffffff81cb2dc0: kexec_purgatory_get_set_symbol.cold (STB_LOCAL)
ffffffff8118fdf0-ffffffff8118fe9a: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:1098
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff81e63b80-ffffffff81e63bc5: kexec_purgatory_get_set_symbol.cold (STB_LOCAL)
ffffffff811bf5b0-ffffffff811bf65a: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81201880)
Location: kernel/kexec_file.c:1102
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff81201880-ffffffff81201964: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81216c50)
Location: kernel/kexec_file.c:1118
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff81216c50-ffffffff81216d34: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8122eb30)
Location: kernel/kexec_file.c:1134
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff8122eb30-ffffffff8122ec14: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (c000000000234680)
Location: kernel/kexec_file.c:1132
Inline: False
Direct callers:
  - arch/powerpc/kernel/machine_kexec_file_64.c:setup_purgatory
  - arch/powerpc/kernel/machine_kexec_file_64.c:setup_purgatory
  - arch/powerpc/kernel/machine_kexec_file_64.c:setup_purgatory
  - arch/powerpc/kernel/machine_kexec_file_64.c:setup_purgatory
  - kernel/kexec_file.c:__se_sys_kexec_file_load
  - kernel/kexec_file.c:__se_sys_kexec_file_load
```
**Symbols:**

```
c000000000234680-c0000000002347e8: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:1132
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff81155224-ffffffff81155270: kexec_purgatory_get_set_symbol.cold (STB_LOCAL)
ffffffff81154540-ffffffff811545ea: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:1132
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff81148544-ffffffff81148590: kexec_purgatory_get_set_symbol.cold (STB_LOCAL)
ffffffff81147860-ffffffff8114790a: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:1132
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff81152ff0-ffffffff8115303c: kexec_purgatory_get_set_symbol.cold (STB_LOCAL)
ffffffff81152320-ffffffff811523ca: kexec_purgatory_get_set_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kexec_purgatory_get_set_symbol(struct kimage *image, const char *name, void *buf, unsigned int size, bool get_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:1132
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
**Symbols:**

```
ffffffff8115fef4-ffffffff8115ff40: kexec_purgatory_get_set_symbol.cold (STB_LOCAL)
ffffffff8115f210-ffffffff8115f2ba: kexec_purgatory_get_set_symbol (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
