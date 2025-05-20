# Function: <code>prb_first_valid_seq</code>

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
u64 prb_first_valid_seq(struct printk_ringbuffer *rb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d1a0)
Location: kernel/printk/printk_ringbuffer.c:1981
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_llseek
```
**Symbols:**

```
ffffffff8111d1a0-ffffffff8111d1f3: prb_first_valid_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 prb_first_valid_seq(struct printk_ringbuffer *rb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d530)
Location: kernel/printk/printk_ringbuffer.c:1981
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_llseek
```
**Symbols:**

```
ffffffff8111d530-ffffffff8111d583: prb_first_valid_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 prb_first_valid_seq(struct printk_ringbuffer *rb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff8113d890)
Location: kernel/printk/printk_ringbuffer.c:1981
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_llseek
```
**Symbols:**

```
ffffffff8113d890-ffffffff8113d8e3: prb_first_valid_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 prb_first_valid_seq(struct printk_ringbuffer *rb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff81160c00)
Location: kernel/printk/printk_ringbuffer.c:1992
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_llseek
```
**Symbols:**

```
ffffffff81160c00-ffffffff81160c5f: prb_first_valid_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 prb_first_valid_seq(struct printk_ringbuffer *rb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff81194180)
Location: kernel/printk/printk_ringbuffer.c:1992
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_llseek
```
**Symbols:**

```
ffffffff81194180-ffffffff811941df: prb_first_valid_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 prb_first_valid_seq(struct printk_ringbuffer *rb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811a59e0)
Location: kernel/printk/printk_ringbuffer.c:1992
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_llseek
```
**Symbols:**

```
ffffffff811a59e0-ffffffff811a5a3f: prb_first_valid_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 prb_first_valid_seq(struct printk_ringbuffer *rb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_ringbuffer.c (ffffffff811b54d0)
Location: kernel/printk/printk_ringbuffer.c:1992
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/nbcon.c:nbcon_init
  - kernel/printk/nbcon.c:nbcon_seq_force
```
**Symbols:**

```
ffffffff811b54d0-ffffffff811b552f: prb_first_valid_seq (STB_GLOBAL)
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
