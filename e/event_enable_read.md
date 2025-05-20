# Function: <code>event_enable_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8115e960)
Location: kernel/trace/trace_events.c:1002
Inline: False
```
**Symbols:**

```
ffffffff8115e960-ffffffff8115eabf: event_enable_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811692a0)
Location: kernel/trace/trace_events.c:1024
Inline: False
```
**Symbols:**

```
ffffffff811692a0-ffffffff811693ff: event_enable_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81174700)
Location: kernel/trace/trace_events.c:993
Inline: False
```
**Symbols:**

```
ffffffff81174700-ffffffff8117485f: event_enable_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81177320)
Location: kernel/trace/trace_events.c:1033
Inline: False
```
**Symbols:**

```
ffffffff81177320-ffffffff811774ab: event_enable_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81184af0)
Location: kernel/trace/trace_events.c:1033
Inline: False
```
**Symbols:**

```
ffffffff81184af0-ffffffff81184c3b: event_enable_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1031
Inline: False
```
**Symbols:**

```
ffffffff81193be0-ffffffff81193d10: event_enable_read (STB_LOCAL)
ffffffff8119648a-ffffffff811964ae: event_enable_read.cold.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1032
Inline: False
```
**Symbols:**

```
ffffffff811a1d40-ffffffff811a1e70: event_enable_read (STB_LOCAL)
ffffffff811a45cb-ffffffff811a45ef: event_enable_read.cold.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1025
Inline: False
```
**Symbols:**

```
ffffffff811afc60-ffffffff811afd93: event_enable_read (STB_LOCAL)
ffffffff811b24ee-ffffffff811b2512: event_enable_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1026
Inline: False
```
**Symbols:**

```
ffffffff811bb2e0-ffffffff811bb413: event_enable_read (STB_LOCAL)
ffffffff811bdb0c-ffffffff811bdb30: event_enable_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1132
Inline: False
```
**Symbols:**

```
ffffffff811d38b0-ffffffff811d39e1: event_enable_read (STB_LOCAL)
ffffffff811d7289-ffffffff811d72ad: event_enable_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1133
Inline: False
```
**Symbols:**

```
ffffffff811d0a00-ffffffff811d0b31: event_enable_read (STB_LOCAL)
ffffffff81be5fee-ffffffff81be6012: event_enable_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1340
Inline: False
```
**Symbols:**

```
ffffffff811d1b90-ffffffff811d1cc1: event_enable_read (STB_LOCAL)
ffffffff81bd7c99-ffffffff81bd7cbd: event_enable_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1341
Inline: False
```
**Symbols:**

```
ffffffff811fe8f0-ffffffff811fea21: event_enable_read (STB_LOCAL)
ffffffff81cb6253-ffffffff81cb6277: event_enable_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1361
Inline: False
```
**Symbols:**

```
ffffffff81239750-ffffffff8123988f: event_enable_read (STB_LOCAL)
ffffffff81e67273-ffffffff81e67297: event_enable_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81286390)
Location: kernel/trace/trace_events.c:1376
Inline: False
```
**Symbols:**

```
ffffffff81286390-ffffffff812864ea: event_enable_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812a2e90)
Location: kernel/trace/trace_events.c:1372
Inline: False
```
**Symbols:**

```
ffffffff812a2e90-ffffffff812a3005: event_enable_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812be780)
Location: kernel/trace/trace_events.c:1381
Inline: False
```
**Symbols:**

```
ffffffff812be780-ffffffff812be8fe: event_enable_read (STB_LOCAL)
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
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffff800010239818)
Location: kernel/trace/trace_events.c:1026
Inline: False
```
**Symbols:**

```
ffff800010239818-ffff80001023997c: event_enable_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0474fd8)
Location: kernel/trace/trace_events.c:1026
Inline: False
```
**Symbols:**

```
c0474fd8-c0475118: event_enable_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0000000002c75d0)
Location: kernel/trace/trace_events.c:1026
Inline: False
```
**Symbols:**

```
c0000000002c75d0-c0000000002c7778: event_enable_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffe0001907be)
Location: kernel/trace/trace_events.c:1026
Inline: False
```
**Symbols:**

```
ffffffe0001907be-ffffffe000190898: event_enable_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1026
Inline: False
```
**Symbols:**

```
ffffffff811b3900-ffffffff811b3a33: event_enable_read (STB_LOCAL)
ffffffff811b612c-ffffffff811b6150: event_enable_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1026
Inline: False
```
**Symbols:**

```
ffffffff811a6700-ffffffff811a6833: event_enable_read (STB_LOCAL)
ffffffff811a8f2c-ffffffff811a8f50: event_enable_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1026
Inline: False
```
**Symbols:**

```
ffffffff811b16d0-ffffffff811b1803: event_enable_read (STB_LOCAL)
ffffffff811b3efc-ffffffff811b3f20: event_enable_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t event_enable_read(struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1026
Inline: False
```
**Symbols:**

```
ffffffff811bf770-ffffffff811bf8a3: event_enable_read (STB_LOCAL)
ffffffff811c1f9c-ffffffff811c1fc0: event_enable_read.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
