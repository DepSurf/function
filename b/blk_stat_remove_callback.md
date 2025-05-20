# Function: <code>blk_stat_remove_callback</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814343e0)
Location: block/blk-stat.c:191
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff814343e0-ffffffff81434453: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81460070)
Location: block/blk-stat.c:160
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff81460070-ffffffff814600e3: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81493a80)
Location: block/blk-stat.c:156
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff81493a80-ffffffff81493afb: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814adc60)
Location: block/blk-stat.c:154
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff814adc60-ffffffff814adcdb: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814dbee0)
Location: block/blk-stat.c:155
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff814dbee0-ffffffff814dbf5b: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814f5310)
Location: block/blk-stat.c:155
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff814f5310-ffffffff814f538b: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81555d20)
Location: block/blk-stat.c:157
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff81555d20-ffffffff81555da3: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81572570)
Location: block/blk-stat.c:157
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff81572570-ffffffff815725f3: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff8157a590)
Location: block/blk-stat.c:157
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff8157a590-ffffffff8157a613: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-stat.c (0)
Location: block/blk-stat.c:157
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff81cd881b-ffffffff81cd8830: blk_stat_remove_callback.cold (STB_LOCAL)
ffffffff815df940-ffffffff815df9d6: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff8168e0b0)
Location: block/blk-stat.c:157
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff8168e0b0-ffffffff8168e140: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff8174c9e0)
Location: block/blk-stat.c:157
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff8174c9e0-ffffffff8174ca70: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81789120)
Location: block/blk-stat.c:157
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff81789120-ffffffff817891b0: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff817cb880)
Location: block/blk-stat.c:157
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff817cb880-ffffffff817cb919: blk_stat_remove_callback (STB_GLOBAL)
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
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffff8000105f5408)
Location: block/blk-stat.c:155
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffff8000105f5408-ffff8000105f54d8: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (c07a0f2c)
Location: block/blk-stat.c:155
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
c07a0f2c-c07a0fbc: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (c00000000078cfe0)
Location: block/blk-stat.c:155
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
c00000000078cfe0-c00000000078d0e0: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffe000433154)
Location: block/blk-stat.c:155
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffe000433154-ffffffe000433204: blk_stat_remove_callback (STB_GLOBAL)
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
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814ed8f0)
Location: block/blk-stat.c:155
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff814ed8f0-ffffffff814ed96b: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814dde40)
Location: block/blk-stat.c:155
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff814dde40-ffffffff814ddebb: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814e9980)
Location: block/blk-stat.c:155
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff814e9980-ffffffff814e99fb: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_stat_remove_callback(struct request_queue *q, struct blk_stat_callback *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81502950)
Location: block/blk-stat.c:155
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-wbt.c:wbt_exit
```
**Symbols:**

```
ffffffff81502950-ffffffff815029c9: blk_stat_remove_callback (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
