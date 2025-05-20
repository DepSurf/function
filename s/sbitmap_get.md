# Function: <code>sbitmap_get</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81482190)
Location: lib/sbitmap.c:112
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffffffff81482190-ffffffff814822a3: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8148b480)
Location: lib/sbitmap.c:114
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffffffff8148b480-ffffffff8148b527: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814c75a0)
Location: lib/sbitmap.c:114
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffffffff814c75a0-ffffffff814c7647: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814f8280)
Location: lib/sbitmap.c:114
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffffffff814f8280-ffffffff814f8327: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8150d330)
Location: lib/sbitmap.c:170
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffffffff8150d330-ffffffff8150d489: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8153ba10)
Location: lib/sbitmap.c:157
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffffffff8153ba10-ffffffff8153bb5a: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8155c820)
Location: lib/sbitmap.c:157
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffffffff8155c820-ffffffff8155c96a: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815e6230)
Location: lib/sbitmap.c:157
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffffffff815e6230-ffffffff815e6376: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8160a420)
Location: lib/sbitmap.c:149
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffffffff8160a420-ffffffff8160a50d: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815ed5e0)
Location: lib/sbitmap.c:231
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff815ed5e0-ffffffff815ed774: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sbitmap_get(struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:231
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff81cdefb7-ffffffff81cdefd2: sbitmap_get.cold (STB_LOCAL)
ffffffff8165a860-ffffffff8165a921: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sbitmap_get(struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:221
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff81ea5483-ffffffff81ea549e: sbitmap_get.cold (STB_LOCAL)
ffffffff817731b0-ffffffff817732aa: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sbitmap_get(struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:221
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff8208dac5-ffffffff8208dae0: sbitmap_get.cold (STB_LOCAL)
ffffffff818a3d80-ffffffff818a3e73: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sbitmap_get(struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:239
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff8210de3e-ffffffff8210dee1: sbitmap_get.cold (STB_LOCAL)
ffffffff818e63f0-ffffffff818e6567: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sbitmap_get(struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:239
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff821eba7b-ffffffff821ebb1e: sbitmap_get.cold (STB_LOCAL)
ffffffff8192d410-ffffffff8192d587: sbitmap_get (STB_GLOBAL)
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
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffff800010669e18)
Location: lib/sbitmap.c:157
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffff800010669e18-ffff800010669f0c: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c08128fc)
Location: lib/sbitmap.c:157
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
c08128fc-c0812a54: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c00000000081fd70)
Location: lib/sbitmap.c:157
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
c00000000081fd70-c00000000081ff78: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffe000494e30)
Location: lib/sbitmap.c:157
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffffffe000494e30-ffffffe000494f4c: sbitmap_get (STB_GLOBAL)
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
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81554e10)
Location: lib/sbitmap.c:157
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffffffff81554e10-ffffffff81554f5a: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81545090)
Location: lib/sbitmap.c:157
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffffffff81545090-ffffffff815451da: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81550b50)
Location: lib/sbitmap.c:157
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffffffff81550b50-ffffffff81550c9a: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint, bool round_robin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8156a990)
Location: lib/sbitmap.c:157
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get
```
**Symbols:**

```
ffffffff8156a990-ffffffff8156aada: sbitmap_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int alloc_hint</code>
</li>
<li>
<b>Param removed. </b>
<code>bool round_robin</code>
</li>
</ul>
</details>
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
