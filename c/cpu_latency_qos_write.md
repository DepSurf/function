# Function: <code>cpu_latency_qos_write</code>

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
ssize_t cpu_latency_qos_write(struct file *filp, const char *buf, size_t count, loff_t *f_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811116a0)
Location: kernel/power/qos.c:378
Inline: False
```
**Symbols:**

```
ffffffff811116a0-ffffffff81111759: cpu_latency_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t cpu_latency_qos_write(struct file *filp, const char *buf, size_t count, loff_t *f_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110e7e0)
Location: kernel/power/qos.c:378
Inline: False
```
**Symbols:**

```
ffffffff8110e7e0-ffffffff8110e873: cpu_latency_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t cpu_latency_qos_write(struct file *filp, const char *buf, size_t count, loff_t *f_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110f2c0)
Location: kernel/power/qos.c:378
Inline: False
```
**Symbols:**

```
ffffffff8110f2c0-ffffffff8110f353: cpu_latency_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t cpu_latency_qos_write(struct file *filp, const char *buf, size_t count, loff_t *f_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8112ec10)
Location: kernel/power/qos.c:378
Inline: False
```
**Symbols:**

```
ffffffff8112ec10-ffffffff8112eca3: cpu_latency_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t cpu_latency_qos_write(struct file *filp, const char *buf, size_t count, loff_t *f_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811500d0)
Location: kernel/power/qos.c:378
Inline: False
```
**Symbols:**

```
ffffffff811500d0-ffffffff81150176: cpu_latency_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t cpu_latency_qos_write(struct file *filp, const char *buf, size_t count, loff_t *f_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8117e9c0)
Location: kernel/power/qos.c:378
Inline: False
```
**Symbols:**

```
ffffffff8117e9c0-ffffffff8117ea66: cpu_latency_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t cpu_latency_qos_write(struct file *filp, const char *buf, size_t count, loff_t *f_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8118f610)
Location: kernel/power/qos.c:378
Inline: False
```
**Symbols:**

```
ffffffff8118f610-ffffffff8118f6b6: cpu_latency_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t cpu_latency_qos_write(struct file *filp, const char *buf, size_t count, loff_t *f_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8119dfb0)
Location: kernel/power/qos.c:383
Inline: False
```
**Symbols:**

```
ffffffff8119dfb0-ffffffff8119e056: cpu_latency_qos_write (STB_LOCAL)
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
