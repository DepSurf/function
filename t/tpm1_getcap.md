# Function: <code>tpm1_getcap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81676e00)
Location: drivers/char/tpm/tpm1-cmd.c:473
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
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
ffffffff81676e00-ffffffff81676f37: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816ac9a0)
Location: drivers/char/tpm/tpm1-cmd.c:467
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff816ac9a0-ffffffff816acbea: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816cf680)
Location: drivers/char/tpm/tpm1-cmd.c:467
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff816cf680-ffffffff816cf8ca: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81784600)
Location: drivers/char/tpm/tpm1-cmd.c:482
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
```
**Symbols:**

```
ffffffff81784600-ffffffff81784837: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8179ba40)
Location: drivers/char/tpm/tpm1-cmd.c:482
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
```
**Symbols:**

```
ffffffff8179ba40-ffffffff8179bc77: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8177e570)
Location: drivers/char/tpm/tpm1-cmd.c:482
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
```
**Symbols:**

```
ffffffff8177e570-ffffffff8177e7a7: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81804770)
Location: drivers/char/tpm/tpm1-cmd.c:482
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
```
**Symbols:**

```
ffffffff81804770-ffffffff818049a7: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81944090)
Location: drivers/char/tpm/tpm1-cmd.c:482
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show
  - drivers/char/tpm/tpm-sysfs.c:owned_show
  - drivers/char/tpm/tpm-sysfs.c:active_show
  - drivers/char/tpm/tpm-sysfs.c:enabled_show
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
```
**Symbols:**

```
ffffffff81944090-ffffffff819442e6: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81aa6d50)
Location: drivers/char/tpm/tpm1-cmd.c:482
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show
  - drivers/char/tpm/tpm-sysfs.c:owned_show
  - drivers/char/tpm/tpm-sysfs.c:active_show
  - drivers/char/tpm/tpm-sysfs.c:enabled_show
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
```
**Symbols:**

```
ffffffff81aa6d50-ffffffff81aa6fa6: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81af2590)
Location: drivers/char/tpm/tpm1-cmd.c:482
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show
  - drivers/char/tpm/tpm-sysfs.c:owned_show
  - drivers/char/tpm/tpm-sysfs.c:active_show
  - drivers/char/tpm/tpm-sysfs.c:enabled_show
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
```
**Symbols:**

```
ffffffff81af2590-ffffffff81af27e6: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81b45b20)
Location: drivers/char/tpm/tpm1-cmd.c:482
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:caps_show
  - drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show
  - drivers/char/tpm/tpm-sysfs.c:owned_show
  - drivers/char/tpm/tpm-sysfs.c:active_show
  - drivers/char/tpm/tpm-sysfs.c:enabled_show
  - drivers/char/tpm/tpm-sysfs.c:pcrs_show
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_update_durations
```
**Symbols:**

```
ffffffff81b45b20-ffffffff81b45d76: tpm1_getcap (STB_GLOBAL)
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
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffff8000108b9bd8)
Location: drivers/char/tpm/tpm1-cmd.c:467
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffff8000108b9bd8-ffff8000108b9e5c: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (c09b2fa8)
Location: drivers/char/tpm/tpm1-cmd.c:467
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
c09b2fa8-c09b3240: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (c00000000095ac80)
Location: drivers/char/tpm/tpm1-cmd.c:467
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
c00000000095ac80-c00000000095afd0: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056a04a)
Location: drivers/char/tpm/tpm1-cmd.c:467
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffe00056a04a-ffffffe00056a57c: tpm1_getcap (STB_GLOBAL)
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
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816950d0)
Location: drivers/char/tpm/tpm1-cmd.c:467
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff816950d0-ffffffff8169531a: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81672ac0)
Location: drivers/char/tpm/tpm1-cmd.c:467
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff81672ac0-ffffffff81672d0a: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816c3340)
Location: drivers/char/tpm/tpm1-cmd.c:467
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff816c3340-ffffffff816c358a: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t tpm1_getcap(struct tpm_chip *chip, u32 subcap_id, cap_t *cap, const char *desc, size_t min_cap_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816dd910)
Location: drivers/char/tpm/tpm1-cmd.c:467
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
**Symbols:**

```
ffffffff816dd910-ffffffff816ddb52: tpm1_getcap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
