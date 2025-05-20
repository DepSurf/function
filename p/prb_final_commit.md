# Function: <code>prb_final_commit</code>

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
void prb_final_commit(struct prb_reserved_entry *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d100)
Location: kernel/printk/printk_ringbuffer.c:1658
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff8111d100-ffffffff8111d115: prb_final_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void prb_final_commit(struct prb_reserved_entry *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d460)
Location: kernel/printk/printk_ringbuffer.c:1658
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff8111d460-ffffffff8111d4af: prb_final_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void prb_final_commit(struct prb_reserved_entry *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (0)
Location: kernel/printk/printk_ringbuffer.c:1658
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff81cad2bd-ffffffff81cad2df: prb_final_commit.cold (STB_LOCAL)
ffffffff8113d790-ffffffff8113d80c: prb_final_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void prb_final_commit(struct prb_reserved_entry *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff81160b20)
Location: kernel/printk/printk_ringbuffer.c:1664
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff81160b20-ffffffff81160b54: prb_final_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void prb_final_commit(struct prb_reserved_entry *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff81194070)
Location: kernel/printk/printk_ringbuffer.c:1664
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff81194070-ffffffff811940a4: prb_final_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void prb_final_commit(struct prb_reserved_entry *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811a58d0)
Location: kernel/printk/printk_ringbuffer.c:1664
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff811a58d0-ffffffff811a5904: prb_final_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void prb_final_commit(struct prb_reserved_entry *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811b53c0)
Location: kernel/printk/printk_ringbuffer.c:1664
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff811b53c0-ffffffff811b53f4: prb_final_commit (STB_GLOBAL)
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
