# Function: <code>prb_init</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void prb_init(struct printk_ringbuffer *rb, char *text_buf, unsigned int textbits, struct prb_desc *descs, unsigned int descbits, struct printk_info *infos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d270)
Location: kernel/printk/printk_ringbuffer.c:2034
Inline: False
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff8111d270-ffffffff8111d36f: prb_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void prb_init(struct printk_ringbuffer *rb, char *text_buf, unsigned int textbits, struct prb_desc *descs, unsigned int descbits, struct printk_info *infos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d5f0)
Location: kernel/printk/printk_ringbuffer.c:2034
Inline: False
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff8111d5f0-ffffffff8111d6ef: prb_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void prb_init(struct printk_ringbuffer *rb, char *text_buf, unsigned int textbits, struct prb_desc *descs, unsigned int descbits, struct printk_info *infos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:2034
Inline: False
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff81cad2df-ffffffff81cad48c: prb_init.cold (STB_LOCAL)
ffffffff8113d950-ffffffff8113da87: prb_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void prb_init(struct printk_ringbuffer *rb, char *text_buf, unsigned int textbits, struct prb_desc *descs, unsigned int descbits, struct printk_info *infos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:2075
Inline: False
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff81e5d7e2-ffffffff81e5d9a3: prb_init.cold (STB_LOCAL)
ffffffff81160d10-ffffffff81160e69: prb_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void prb_init(struct printk_ringbuffer *rb, char *text_buf, unsigned int textbits, struct prb_desc *descs, unsigned int descbits, struct printk_info *infos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:2075
Inline: False
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff82059772-ffffffff82059933: prb_init.cold (STB_LOCAL)
ffffffff811942b0-ffffffff81194409: prb_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void prb_init(struct printk_ringbuffer *rb, char *text_buf, unsigned int textbits, struct prb_desc *descs, unsigned int descbits, struct printk_info *infos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:2075
Inline: False
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff820d7d97-ffffffff820d7f58: prb_init.cold (STB_LOCAL)
ffffffff811a5b10-ffffffff811a5c69: prb_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void prb_init(struct printk_ringbuffer *rb, char *text_buf, unsigned int textbits, struct prb_desc *descs, unsigned int descbits, struct printk_info *infos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:2075
Inline: False
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
```
**Symbols:**

```
ffffffff821b3018-ffffffff821b31d9: prb_init.cold (STB_LOCAL)
ffffffff811b5600-ffffffff811b5759: prb_init (STB_GLOBAL)
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
