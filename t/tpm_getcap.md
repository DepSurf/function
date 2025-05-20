# Function: <code>tpm_getcap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t tpm_getcap(struct device *dev, __be32 subcap_id, cap_t *cap, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81524810)
Location: drivers/char/tpm/tpm-interface.c:435
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show
  - drivers/char/tpm/tpm-sysfs.c:owned_show
  - drivers/char/tpm/tpm-sysfs.c:active_show
  - drivers/char/tpm/tpm-sysfs.c:enabled_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
```
**Symbols:**

```
ffffffff81524810-ffffffff8152490e: tpm_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t tpm_getcap(struct tpm_chip *chip, __be32 subcap_id, cap_t *cap, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81577790)
Location: drivers/char/tpm/tpm-interface.c:435
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show
  - drivers/char/tpm/tpm-sysfs.c:owned_show
  - drivers/char/tpm/tpm-sysfs.c:active_show
  - drivers/char/tpm/tpm-sysfs.c:enabled_show
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
```
**Symbols:**

```
ffffffff81577790-ffffffff81577887: tpm_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t tpm_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815a3200)
Location: drivers/char/tpm/tpm-interface.c:447
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show
  - drivers/char/tpm/tpm-sysfs.c:owned_show
  - drivers/char/tpm/tpm-sysfs.c:active_show
  - drivers/char/tpm/tpm-sysfs.c:enabled_show
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff815a3200-ffffffff815a32f6: tpm_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t tpm_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff815b6f60)
Location: drivers/char/tpm/tpm-interface.c:596
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show
  - drivers/char/tpm/tpm-sysfs.c:owned_show
  - drivers/char/tpm/tpm-sysfs.c:active_show
  - drivers/char/tpm/tpm-sysfs.c:enabled_show
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff815b6f60-ffffffff815b71d0: tpm_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t tpm_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161dd00)
Location: drivers/char/tpm/tpm-interface.c:614
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show
  - drivers/char/tpm/tpm-sysfs.c:owned_show
  - drivers/char/tpm/tpm-sysfs.c:active_show
  - drivers/char/tpm/tpm-sysfs.c:enabled_show
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff8161dd00-ffffffff8161de37: tpm_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t tpm_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81657a10)
Location: drivers/char/tpm/tpm-interface.c:733
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show
  - drivers/char/tpm/tpm-sysfs.c:owned_show
  - drivers/char/tpm/tpm-sysfs.c:active_show
  - drivers/char/tpm/tpm-sysfs.c:enabled_show
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff81657a10-ffffffff81657b47: tpm_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_chip *chip</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>__be32 subcap_id</code> ➡️ <code>u32 subcap_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t min_cap_length</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
