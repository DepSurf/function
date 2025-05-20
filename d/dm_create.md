# Function: <code>dm_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a32d0)
Location: drivers/md/dm.c:2541
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff816a32d0-ffffffff816a374a: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81703b30)
Location: drivers/md/dm.c:1713
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff81703b30-ffffffff81704028: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817359f0)
Location: drivers/md/dm.c:1770
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff817359f0-ffffffff81735ee5: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174ee20)
Location: drivers/md/dm.c:1977
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff8174ee20-ffffffff8174f341: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817c1040)
Location: drivers/md/dm.c:1956
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff817c1040-ffffffff817c15be: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2136
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff8180aa5d-ffffffff8180aa73: dm_create.cold.58 (STB_LOCAL)
ffffffff818096d0-ffffffff81809c54: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2176
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
```
**Symbols:**

```
ffffffff81836a5d-ffffffff81836a73: dm_create.cold.62 (STB_LOCAL)
ffffffff818357e0-ffffffff81835cc8: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81878800)
Location: drivers/md/dm.c:2207
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81878800-ffffffff81878856: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818aa640)
Location: drivers/md/dm.c:2205
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818aa640-ffffffff818aa696: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197a940)
Location: drivers/md/dm.c:2208
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8197a940-ffffffff8197a996: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197f180)
Location: drivers/md/dm.c:2082
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8197f180-ffffffff8197f1d6: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff819632a0)
Location: drivers/md/dm.c:2101
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff819632a0-ffffffff819632f6: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a0b390)
Location: drivers/md/dm.c:1987
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81a0b390-ffffffff81a0b3c6: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b73790)
Location: drivers/md/dm.c:2167
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81b73790-ffffffff81b737ce: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d10390)
Location: drivers/md/dm.c:2245
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81d10390-ffffffff81d103ce: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d79800)
Location: drivers/md/dm.c:2291
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81d79800-ffffffff81d7983e: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e309a0)
Location: drivers/md/dm.c:2299
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81e309a0-ffffffff81e309de: dm_create (STB_GLOBAL)
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
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010b00598)
Location: drivers/md/dm.c:2205
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffff800010b00598-ffff800010b00610: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0be0010)
Location: drivers/md/dm.c:2205
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
c0be0010-c0be0064: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000befa30)
Location: drivers/md/dm.c:2205
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
c000000000befa30-c000000000befad0: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006f0aa0)
Location: drivers/md/dm.c:2205
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffe0006f0aa0-ffffffe0006f0b08: dm_create (STB_GLOBAL)
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
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818504c0)
Location: drivers/md/dm.c:2205
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818504c0-ffffffff81850516: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81817ad0)
Location: drivers/md/dm.c:2205
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81817ad0-ffffffff81817b26: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189faf0)
Location: drivers/md/dm.c:2205
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8189faf0-ffffffff8189fb46: dm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dm_create(int minor, struct mapped_device **result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818bbd50)
Location: drivers/md/dm.c:2205
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_create
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818bbd50-ffffffff818bbda6: dm_create (STB_GLOBAL)
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
