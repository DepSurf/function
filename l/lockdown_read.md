# Function: <code>lockdown_read</code>

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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:118
Inline: False
```
**Symbols:**

```
ffffffff814b3880-ffffffff814b3986: lockdown_read (STB_LOCAL)
ffffffff814b3a17-ffffffff814b3a2f: lockdown_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:96
Inline: False
```
**Symbols:**

```
ffffffff81512db0-ffffffff81512eb9: lockdown_read (STB_LOCAL)
ffffffff81512f4b-ffffffff81512f63: lockdown_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:96
Inline: False
```
**Symbols:**

```
ffffffff8152ff80-ffffffff81530089: lockdown_read (STB_LOCAL)
ffffffff81bf1993-ffffffff81bf19ab: lockdown_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:96
Inline: False
```
**Symbols:**

```
ffffffff81536180-ffffffff81536289: lockdown_read (STB_LOCAL)
ffffffff81be39b1-ffffffff81be39c9: lockdown_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:96
Inline: False
```
**Symbols:**

```
ffffffff815947b0-ffffffff81594953: lockdown_read (STB_LOCAL)
ffffffff81cd6ae4-ffffffff81cd6afc: lockdown_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:96
Inline: False
```
**Symbols:**

```
ffffffff816368a0-ffffffff81636a6b: lockdown_read (STB_LOCAL)
ffffffff81e89a28-ffffffff81e89a40: lockdown_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff816ed9f0)
Location: security/lockdown/lockdown.c:98
Inline: False
```
**Symbols:**

```
ffffffff816ed9f0-ffffffff816edbd3: lockdown_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff81727e00)
Location: security/lockdown/lockdown.c:98
Inline: False
```
**Symbols:**

```
ffffffff81727e00-ffffffff81727fe3: lockdown_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff81769130)
Location: security/lockdown/lockdown.c:97
Inline: False
```
**Symbols:**

```
ffffffff81769130-ffffffff81769313: lockdown_read (STB_LOCAL)
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
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffff8000105ab5c0)
Location: security/lockdown/lockdown.c:118
Inline: False
```
**Symbols:**

```
ffff8000105ab5c0-ffff8000105ab71c: lockdown_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (c075b178)
Location: security/lockdown/lockdown.c:118
Inline: False
```
**Symbols:**

```
c075b178-c075b2b8: lockdown_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (c0000000007295b0)
Location: security/lockdown/lockdown.c:118
Inline: False
```
**Symbols:**

```
c0000000007295b0-c0000000007297a8: lockdown_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffe0003f413a)
Location: security/lockdown/lockdown.c:118
Inline: False
```
**Symbols:**

```
ffffffe0003f413a-ffffffe0003f4244: lockdown_read (STB_LOCAL)
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
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:118
Inline: False
```
**Symbols:**

```
ffffffff814abe60-ffffffff814abf66: lockdown_read (STB_LOCAL)
ffffffff814abff7-ffffffff814ac00f: lockdown_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:118
Inline: False
```
**Symbols:**

```
ffffffff8149c880-ffffffff8149c986: lockdown_read (STB_LOCAL)
ffffffff8149ca17-ffffffff8149ca2f: lockdown_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:118
Inline: False
```
**Symbols:**

```
ffffffff814a7f00-ffffffff814a8006: lockdown_read (STB_LOCAL)
ffffffff814a8097-ffffffff814a80af: lockdown_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t lockdown_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (0)
Location: security/lockdown/lockdown.c:118
Inline: False
```
**Symbols:**

```
ffffffff814c0890-ffffffff814c0996: lockdown_read (STB_LOCAL)
ffffffff814c0a27-ffffffff814c0a3f: lockdown_read.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
