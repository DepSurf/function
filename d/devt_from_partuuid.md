# Function: <code>devt_from_partuuid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002348)
Location: init/do_mounts.c:116
Inline: True
Inline callers:
  - init/do_mounts.c:name_to_dev_t
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff810023a8)
Location: init/do_mounts.c:116
Inline: True
Inline callers:
  - init/do_mounts.c:name_to_dev_t
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff810023c8)
Location: init/do_mounts.c:116
Inline: True
Inline callers:
  - init/do_mounts.c:name_to_dev_t
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff8100257d)
Location: init/do_mounts.c:116
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff810025ad)
Location: init/do_mounts.c:116
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002ce0)
Location: init/do_mounts.c:116
Inline: True
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
In init/do_mounts.c (ffffffff81002d28)
Location: init/do_mounts.c:107
Inline: True
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
In init/do_mounts.c (ffffffff81002e4e)
Location: init/do_mounts.c:108
Inline: True
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
In init/do_mounts.c (ffffffff81002e3e)
Location: init/do_mounts.c:108
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
dev_t devt_from_partuuid(const char *uuid_str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (0)
Location: init/do_mounts.c:108
Inline: False
```
**Symbols:**

```
ffffffff81003d00-ffffffff81003e36: devt_from_partuuid (STB_LOCAL)
ffffffff810041fb-ffffffff8100422e: devt_from_partuuid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
dev_t devt_from_partuuid(const char *uuid_str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (0)
Location: init/do_mounts.c:101
Inline: False
```
**Symbols:**

```
ffffffff81003b60-ffffffff81003c73: devt_from_partuuid (STB_LOCAL)
ffffffff81bd1831-ffffffff81bd1864: devt_from_partuuid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
dev_t devt_from_partuuid(const char *uuid_str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (0)
Location: init/do_mounts.c:101
Inline: False
```
**Symbols:**

```
ffffffff81003b40-ffffffff81003c56: devt_from_partuuid (STB_LOCAL)
ffffffff81bc3841-ffffffff81bc3874: devt_from_partuuid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
dev_t devt_from_partuuid(const char *uuid_str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (0)
Location: init/do_mounts.c:101
Inline: False
```
**Symbols:**

```
ffffffff81003b80-ffffffff81003c83: devt_from_partuuid (STB_LOCAL)
ffffffff81c948a7-ffffffff81c948da: devt_from_partuuid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
dev_t devt_from_partuuid(const char *uuid_str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (0)
Location: init/do_mounts.c:100
Inline: False
```
**Symbols:**

```
ffffffff81001820-ffffffff81001932: devt_from_partuuid (STB_LOCAL)
ffffffff81e43a27-ffffffff81e43a58: devt_from_partuuid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
dev_t devt_from_partuuid(const char *uuid_str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81001ea0)
Location: init/do_mounts.c:100
Inline: False
```
**Symbols:**

```
ffffffff81001ea0-ffffffff81001feb: devt_from_partuuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devt_from_partuuid(const char *uuid_str, dev_t *devt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/early-lookup.c (ffffffff836fdc50)
Location: block/early-lookup.c:46
Inline: False
Direct callers:
  - block/early-lookup.c:early_lookup_bdev
```
**Symbols:**

```
ffffffff836fdc50-ffffffff836fdd7e: devt_from_partuuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devt_from_partuuid(const char *uuid_str, dev_t *devt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/early-lookup.c (ffffffff83931330)
Location: block/early-lookup.c:46
Inline: False
Direct callers:
  - block/early-lookup.c:early_lookup_bdev
```
**Symbols:**

```
ffffffff83931330-ffffffff8393145e: devt_from_partuuid (STB_LOCAL)
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
In init/do_mounts.c (ffff8000100854b8)
Location: init/do_mounts.c:108
Inline: True
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
In init/do_mounts.c (c0303c5c)
Location: init/do_mounts.c:108
Inline: True
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
In init/do_mounts.c (c000000000010e14)
Location: init/do_mounts.c:108
Inline: True
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
In init/do_mounts.c (ffffffe0000b48b6)
Location: init/do_mounts.c:108
Inline: True
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
In init/do_mounts.c (ffffffff81002e3e)
Location: init/do_mounts.c:108
Inline: True
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
In init/do_mounts.c (ffffffff8100131e)
Location: init/do_mounts.c:108
Inline: True
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
In init/do_mounts.c (ffffffff81002e3e)
Location: init/do_mounts.c:108
Inline: True
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
In init/do_mounts.c (ffffffff81002e8e)
Location: init/do_mounts.c:108
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>dev_t *devt</code>
</li>
<li>
<b>Return type changed. </b>
<code>dev_t</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
