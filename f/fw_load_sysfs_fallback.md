# Function: <code>fw_load_sysfs_fallback</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8169bb1c)
Location: drivers/base/firmware_loader/fallback.c:547
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816bc3bf)
Location: drivers/base/firmware_loader/fallback.c:542
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816f6a24)
Location: drivers/base/firmware_loader/fallback.c:495
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8171ae17)
Location: drivers/base/firmware_loader/fallback.c:495
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs *fw_sysfs, u32 opt_flags, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:498
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
```
**Symbols:**

```
ffffffff817d69d0-ffffffff817d6bb2: fw_load_sysfs_fallback (STB_LOCAL)
ffffffff817d709d-ffffffff817d70b8: fw_load_sysfs_fallback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs *fw_sysfs, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:497
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
```
**Symbols:**

```
ffffffff817eb580-ffffffff817eb758: fw_load_sysfs_fallback (STB_LOCAL)
ffffffff81c0f25e-ffffffff81c0f279: fw_load_sysfs_fallback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs *fw_sysfs, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:495
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
```
**Symbols:**

```
ffffffff817cfd40-ffffffff817cff33: fw_load_sysfs_fallback (STB_LOCAL)
ffffffff81c013b7-ffffffff81c013d2: fw_load_sysfs_fallback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs *fw_sysfs, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:495
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
```
**Symbols:**

```
ffffffff8185a550-ffffffff8185a752: fw_load_sysfs_fallback (STB_LOCAL)
ffffffff81d04368-ffffffff81d04398: fw_load_sysfs_fallback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs *fw_sysfs, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:70
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff819a0a60-ffffffff819a0c6c: fw_load_sysfs_fallback (STB_LOCAL)
ffffffff81eccc64-ffffffff81eccc94: fw_load_sysfs_fallback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs *fw_sysfs, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:70
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff81b12680-ffffffff81b128c9: fw_load_sysfs_fallback (STB_LOCAL)
ffffffff82098b68-ffffffff82098b7c: fw_load_sysfs_fallback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs *fw_sysfs, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:70
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff81b60970-ffffffff81b60bb9: fw_load_sysfs_fallback (STB_LOCAL)
ffffffff82119b1f-ffffffff82119b33: fw_load_sysfs_fallback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fw_load_sysfs_fallback(struct fw_sysfs *fw_sysfs, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:74
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff81bb43b0-ffffffff81bb45ff: fw_load_sysfs_fallback (STB_LOCAL)
ffffffff821f79f7-ffffffff821f7a20: fw_load_sysfs_fallback.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffff80001090e6d8)
Location: drivers/base/firmware_loader/fallback.c:495
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (c09f7550)
Location: drivers/base/firmware_loader/fallback.c:495
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (c0000000009aef50)
Location: drivers/base/firmware_loader/fallback.c:495
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffe000592d6a)
Location: drivers/base/firmware_loader/fallback.c:495
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816e1147)
Location: drivers/base/firmware_loader/fallback.c:495
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816bb787)
Location: drivers/base/firmware_loader/fallback.c:495
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8170e817)
Location: drivers/base/firmware_loader/fallback.c:495
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff81729437)
Location: drivers/base/firmware_loader/fallback.c:495
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 opt_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>fw_sysfs, opt_flags, timeout</code> ➡️ <code>fw_sysfs, timeout</code>
</li>
</ul>
</details>
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
