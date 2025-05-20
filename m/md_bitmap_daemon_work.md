# Function: <code>md_bitmap_daemon_work</code>

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
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81830d70)
Location: drivers/md/md-bitmap.c:1229
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff81830d70-ffffffff818310db: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818738e0)
Location: drivers/md/md-bitmap.c:1230
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff818738e0-ffffffff81873c67: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818a56e0)
Location: drivers/md/md-bitmap.c:1230
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff818a56e0-ffffffff818a5a71: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81975600)
Location: drivers/md/md-bitmap.c:1224
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff81975600-ffffffff81975996: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8197a5f0)
Location: drivers/md/md-bitmap.c:1225
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff8197a5f0-ffffffff8197a98c: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8195e810)
Location: drivers/md/md-bitmap.c:1225
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff8195e810-ffffffff8195ebab: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1225
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff81d29b21-ffffffff81d29b5f: md_bitmap_daemon_work.cold (STB_LOCAL)
ffffffff81a04120-ffffffff81a044d3: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1226
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff81ef5e88-ffffffff81ef5ec6: md_bitmap_daemon_work.cold (STB_LOCAL)
ffffffff81b6bd80-ffffffff81b6c13f: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1226
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff820a84a9-ffffffff820a84e7: md_bitmap_daemon_work.cold (STB_LOCAL)
ffffffff81d07db0-ffffffff81d08173: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1286
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff821296be-ffffffff821296fc: md_bitmap_daemon_work.cold (STB_LOCAL)
ffffffff81d70f40-ffffffff81d7130e: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1291
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff8220b05d-ffffffff8220b09b: md_bitmap_daemon_work.cold (STB_LOCAL)
ffffffff81e27ff0-ffffffff81e283bc: md_bitmap_daemon_work (STB_GLOBAL)
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
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010afa490)
Location: drivers/md/md-bitmap.c:1230
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffff800010afa490-ffff800010afa8c4: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bdafe8)
Location: drivers/md/md-bitmap.c:1230
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
c0bdafe8-c0bdb3e8: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be82f0)
Location: drivers/md/md-bitmap.c:1230
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
c000000000be82f0-c000000000be883c: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006ebed4)
Location: drivers/md/md-bitmap.c:1230
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffe0006ebed4-ffffffe0006ec242: md_bitmap_daemon_work (STB_GLOBAL)
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
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8184b560)
Location: drivers/md/md-bitmap.c:1230
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff8184b560-ffffffff8184b8f1: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81812b90)
Location: drivers/md/md-bitmap.c:1230
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff81812b90-ffffffff81812f1b: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8189ab90)
Location: drivers/md/md-bitmap.c:1230
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff8189ab90-ffffffff8189af21: md_bitmap_daemon_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void md_bitmap_daemon_work(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818b6d20)
Location: drivers/md/md-bitmap.c:1230
Inline: False
Direct callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:md_bitmap_flush
```
**Symbols:**

```
ffffffff818b6d20-ffffffff818b70a9: md_bitmap_daemon_work (STB_GLOBAL)
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
