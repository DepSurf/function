# Function: <code>io_bitmap_share</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void io_bitmap_share(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff810370b0)
Location: arch/x86/kernel/ioport.c:22
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread_tls
```
**Symbols:**

```
ffffffff810370b0-ffffffff8103712a: io_bitmap_share (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_bitmap_share(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81038170)
Location: arch/x86/kernel/ioport.c:22
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
```
**Symbols:**

```
ffffffff81038170-ffffffff810381ea: io_bitmap_share (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_bitmap_share(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81039cb0)
Location: arch/x86/kernel/ioport.c:22
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
```
**Symbols:**

```
ffffffff81039cb0-ffffffff81039d2a: io_bitmap_share (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_bitmap_share(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff8103f660)
Location: arch/x86/kernel/ioport.c:22
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
```
**Symbols:**

```
ffffffff8103f660-ffffffff8103f6da: io_bitmap_share (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_bitmap_share(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81046d60)
Location: arch/x86/kernel/ioport.c:22
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
```
**Symbols:**

```
ffffffff81046d60-ffffffff81046de6: io_bitmap_share (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_bitmap_share(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81050ea0)
Location: arch/x86/kernel/ioport.c:22
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
```
**Symbols:**

```
ffffffff81050ea0-ffffffff81050f26: io_bitmap_share (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_bitmap_share(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81051bd0)
Location: arch/x86/kernel/ioport.c:22
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
```
**Symbols:**

```
ffffffff81051bd0-ffffffff81051c56: io_bitmap_share (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_bitmap_share(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81058df0)
Location: arch/x86/kernel/ioport.c:22
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
```
**Symbols:**

```
ffffffff81058df0-ffffffff81058e76: io_bitmap_share (STB_GLOBAL)
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
