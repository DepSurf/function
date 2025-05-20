# Function: <code>hwlat_mode_write</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t hwlat_mode_write(struct file *filp, const char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:683
Inline: False
```
**Symbols:**

```
ffffffff811f6f90-ffffffff811f714c: hwlat_mode_write (STB_LOCAL)
ffffffff81cb5ef1-ffffffff81cb5f1b: hwlat_mode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t hwlat_mode_write(struct file *filp, const char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:679
Inline: False
```
**Symbols:**

```
ffffffff81230a50-ffffffff81230c33: hwlat_mode_write (STB_LOCAL)
ffffffff81e66f12-ffffffff81e66f3c: hwlat_mode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t hwlat_mode_write(struct file *filp, const char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:679
Inline: False
```
**Symbols:**

```
ffffffff8127cdf0-ffffffff8127cfd3: hwlat_mode_write (STB_LOCAL)
ffffffff8205de92-ffffffff8205debc: hwlat_mode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t hwlat_mode_write(struct file *filp, const char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:680
Inline: False
```
**Symbols:**

```
ffffffff812946b0-ffffffff812948b1: hwlat_mode_write (STB_LOCAL)
ffffffff820dc7e2-ffffffff820dc80c: hwlat_mode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t hwlat_mode_write(struct file *filp, const char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:680
Inline: False
```
**Symbols:**

```
ffffffff812afd10-ffffffff812aff11: hwlat_mode_write (STB_LOCAL)
ffffffff821b8612-ffffffff821b863c: hwlat_mode_write.cold (STB_LOCAL)
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
