# Function: <code>lstats_write</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t lstats_write(struct file *file, const char *buf, size_t count, loff_t *offs);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/latencytop.c (ffffffff81282000)
Location: kernel/latencytop.c:271
Inline: False
```
```
In fs/proc/base.c (ffffffff815a48f0)
Location: fs/proc/base.c:528
Inline: False
```
**Symbols:**

```
ffffffff81282000-ffffffff81282052: lstats_write (STB_LOCAL)
ffffffff815a48f0-ffffffff815a4969: lstats_write (STB_LOCAL)
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
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t lstats_write(struct file *file, const char *buf, size_t count, loff_t *offs);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/latencytop.c (ffffffff8119a6c0)
Location: kernel/latencytop.c:245
Inline: False
```
```
In fs/proc/base.c (ffffffff8137d020)
Location: fs/proc/base.c:524
Inline: False
```
**Symbols:**

```
ffffffff8119a6c0-ffffffff8119a70a: lstats_write (STB_LOCAL)
ffffffff8137d020-ffffffff8137d075: lstats_write (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>
