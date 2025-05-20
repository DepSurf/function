# Function: <code>inotify_fdinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff81250fb0)
Location: fs/notify/fdinfo.c:74
Inline: True
```
**Symbols:**

```
ffffffff81250fb0-ffffffff8125103e: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff812797b0)
Location: fs/notify/fdinfo.c:74
Inline: True
```
**Symbols:**

```
ffffffff812797b0-ffffffff8127983e: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff8128d370)
Location: fs/notify/fdinfo.c:74
Inline: True
```
**Symbols:**

```
ffffffff8128d370-ffffffff8128d3fe: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff8129a1f0)
Location: fs/notify/fdinfo.c:74
Inline: False
```
**Symbols:**

```
ffffffff8129a1f0-ffffffff8129a27a: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff812bd5c0)
Location: fs/notify/fdinfo.c:75
Inline: False
```
**Symbols:**

```
ffffffff812bd5c0-ffffffff812bd64a: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff812e6230)
Location: fs/notify/fdinfo.c:75
Inline: False
```
**Symbols:**

```
ffffffff812e6230-ffffffff812e62ba: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff812fadd0)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
ffffffff812fadd0-ffffffff812fae60: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff8131b680)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
ffffffff8131b680-ffffffff8131b711: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff8132e440)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
ffffffff8132e440-ffffffff8132e4d1: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff81368300)
Location: fs/notify/fdinfo.c:75
Inline: False
Direct callers:
  - fs/notify/fdinfo.c:inotify_show_fdinfo
```
**Symbols:**

```
ffffffff81368300-ffffffff81368391: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff81375630)
Location: fs/notify/fdinfo.c:75
Inline: False
Direct callers:
  - fs/notify/fdinfo.c:inotify_show_fdinfo
```
**Symbols:**

```
ffffffff81375630-ffffffff813756c1: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff8137bfd0)
Location: fs/notify/fdinfo.c:75
Inline: False
Direct callers:
  - fs/notify/fdinfo.c:inotify_show_fdinfo
```
**Symbols:**

```
ffffffff8137bfd0-ffffffff8137c061: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff813c8e20)
Location: fs/notify/fdinfo.c:75
Inline: False
Direct callers:
  - fs/notify/fdinfo.c:inotify_show_fdinfo
```
**Symbols:**

```
ffffffff813c8e20-ffffffff813c8eb1: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff81450890)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
ffffffff81450890-ffffffff8145095e: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff814df2a0)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
ffffffff814df2a0-ffffffff814df36e: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff81515b30)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
ffffffff81515b30-ffffffff81515bfe: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff81549ef0)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
ffffffff81549ef0-ffffffff81549fbe: inotify_fdinfo (STB_LOCAL)
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
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffff8000103ead18)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
ffff8000103ead18-ffff8000103eadc4: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (c05c1e5c)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
c05c1e5c-c05c1f08: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (c0000000004f1e50)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
c0000000004f1e50-c0000000004f1f1c: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffe00029f1f0)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
ffffffe00029f1f0-ffffffe00029f288: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff81326a20)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
ffffffff81326a20-ffffffff81326ab1: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff813175c0)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
ffffffff813175c0-ffffffff81317651: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff813244f0)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
ffffffff813244f0-ffffffff81324581: inotify_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inotify_fdinfo(struct seq_file *m, struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fdinfo.c (ffffffff81336270)
Location: fs/notify/fdinfo.c:76
Inline: False
```
**Symbols:**

```
ffffffff81336270-ffffffff81336301: inotify_fdinfo (STB_LOCAL)
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
