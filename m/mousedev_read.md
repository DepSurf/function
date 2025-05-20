# Function: <code>mousedev_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff8166b780)
Location: drivers/input/mousedev.c:712
Inline: False
```
**Symbols:**

```
ffffffff8166b780-ffffffff8166b9e3: mousedev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff816cc4b0)
Location: drivers/input/mousedev.c:712
Inline: False
```
**Symbols:**

```
ffffffff816cc4b0-ffffffff816cc76e: mousedev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff816fa460)
Location: drivers/input/mousedev.c:712
Inline: False
```
**Symbols:**

```
ffffffff816fa460-ffffffff816fa710: mousedev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff8170ff90)
Location: drivers/input/mousedev.c:712
Inline: False
```
**Symbols:**

```
ffffffff8170ff90-ffffffff81710199: mousedev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff81781210)
Location: drivers/input/mousedev.c:718
Inline: False
```
**Symbols:**

```
ffffffff81781210-ffffffff81781419: mousedev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:718
Inline: False
```
**Symbols:**

```
ffffffff817c1a60-ffffffff817c1c65: mousedev_read (STB_LOCAL)
ffffffff817c2d02-ffffffff817c2d0e: mousedev_read.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:719
Inline: False
```
**Symbols:**

```
ffffffff817e8f50-ffffffff817e9155: mousedev_read (STB_LOCAL)
ffffffff817ea2a0-ffffffff817ea2ac: mousedev_read.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffff81829860-ffffffff81829a68: mousedev_read (STB_LOCAL)
ffffffff8182ada8-ffffffff8182adb4: mousedev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffff8185b1f0-ffffffff8185b3f8: mousedev_read (STB_LOCAL)
ffffffff8185c738-ffffffff8185c744: mousedev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffff8192ec50-ffffffff8192ee5b: mousedev_read (STB_LOCAL)
ffffffff8192f516-ffffffff8192f522: mousedev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffff81935ff0-ffffffff819361fb: mousedev_read (STB_LOCAL)
ffffffff81c23534-ffffffff81c23540: mousedev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffff81919eb0-ffffffff8191a0bb: mousedev_read (STB_LOCAL)
ffffffff81c1560a-ffffffff81c15616: mousedev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffff819bc2b0-ffffffff819bc4fe: mousedev_read (STB_LOCAL)
ffffffff81d2367d-ffffffff81d236eb: mousedev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffff81b1b910-ffffffff81b1bb88: mousedev_read (STB_LOCAL)
ffffffff81eef3fe-ffffffff81eef47b: mousedev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffff81cad700-ffffffff81cad97f: mousedev_read (STB_LOCAL)
ffffffff820a6968-ffffffff820a69d9: mousedev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffff81d14ce0-ffffffff81d14f68: mousedev_read (STB_LOCAL)
ffffffff82127d75-ffffffff82127de6: mousedev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffff81dca900-ffffffff81dcab88: mousedev_read (STB_LOCAL)
ffffffff822096f6-ffffffff82209767: mousedev_read.cold (STB_LOCAL)
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
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffff800010a9c728)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffff800010a9c728-ffff800010a9ca74: mousedev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (c0b7d230)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
c0b7d230-c0b7d468: mousedev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (c000000000b7bba0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
c000000000b7bba0-c000000000b7be6c: mousedev_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffe0006acea8)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffe0006acea8-ffffffe0006ad07c: mousedev_read (STB_LOCAL)
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
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffff81810200-ffffffff81810408: mousedev_read (STB_LOCAL)
ffffffff81811748-ffffffff81811754: mousedev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffff817d7950-ffffffff817d7b52: mousedev_read (STB_LOCAL)
ffffffff817d8e88-ffffffff817d8e94: mousedev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffff8184f380-ffffffff8184f588: mousedev_read (STB_LOCAL)
ffffffff818508c8-ffffffff818508d4: mousedev_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t mousedev_read(struct file *file, char *buffer, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:716
Inline: False
```
**Symbols:**

```
ffffffff8186a7c0-ffffffff8186a998: mousedev_read (STB_LOCAL)
ffffffff8186ba48-ffffffff8186ba54: mousedev_read.cold (STB_LOCAL)
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
