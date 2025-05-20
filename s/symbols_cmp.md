# Function: <code>symbols_cmp</code>

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
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int symbols_cmp(const void *a, const void *b);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81209350)
Location: kernel/trace/ftrace.c:8023
Inline: False
```
```
In kernel/trace/fprobe.c (ffffffff81268490)
Location: kernel/trace/fprobe.c:88
Inline: False
```
**Symbols:**

```
ffffffff81209350-ffffffff81209369: symbols_cmp (STB_LOCAL)
ffffffff81268490-ffffffff812684a9: symbols_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int symbols_cmp(const void *a, const void *b);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812519c0)
Location: kernel/trace/ftrace.c:8276
Inline: False
```
```
In kernel/trace/fprobe.c (ffffffff812ba690)
Location: kernel/trace/fprobe.c:88
Inline: False
```
**Symbols:**

```
ffffffff812519c0-ffffffff812519d9: symbols_cmp (STB_LOCAL)
ffffffff812ba690-ffffffff812ba6a9: symbols_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int symbols_cmp(const void *a, const void *b);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81268de0)
Location: kernel/trace/ftrace.c:8091
Inline: False
```
```
In kernel/trace/fprobe.c (ffffffff812ddca0)
Location: kernel/trace/fprobe.c:150
Inline: False
```
**Symbols:**

```
ffffffff81268de0-ffffffff81268df9: symbols_cmp (STB_LOCAL)
ffffffff812ddca0-ffffffff812ddcb9: symbols_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int symbols_cmp(const void *a, const void *b);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81282f10)
Location: kernel/trace/ftrace.c:8091
Inline: False
```
```
In kernel/trace/fprobe.c (ffffffff812fbd90)
Location: kernel/trace/fprobe.c:150
Inline: False
```
**Symbols:**

```
ffffffff81282f10-ffffffff81282f29: symbols_cmp (STB_LOCAL)
ffffffff812fbd90-ffffffff812fbda9: symbols_cmp (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
