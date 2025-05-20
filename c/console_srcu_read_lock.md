# Function: <code>console_srcu_read_lock</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int console_srcu_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811924a4)
Location: kernel/printk/printk.c:288
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_flush_all
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8118d420-ffffffff8118d43d: console_srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int console_srcu_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a3d44)
Location: kernel/printk/printk.c:290
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_flush_all
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff8119ebf0-ffffffff8119ec0d: console_srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int console_srcu_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b33d0)
Location: kernel/printk/printk.c:284
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_flush_all
Direct callers:
  - drivers/tty/serial/kgdboc.c:configure_kgdboc
```
**Symbols:**

```
ffffffff811addb0-ffffffff811addcd: console_srcu_read_lock (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
