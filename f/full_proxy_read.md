# Function: <code>full_proxy_read</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81352e50)
Location: fs/debugfs/file.c:161
Inline: False
```
**Symbols:**

```
ffffffff81352e50-ffffffff81352ed7: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81369100)
Location: fs/debugfs/file.c:158
Inline: False
```
**Symbols:**

```
ffffffff81369100-ffffffff81369187: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8137d780)
Location: fs/debugfs/file.c:158
Inline: False
```
**Symbols:**

```
ffffffff8137d780-ffffffff8137d807: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813a3580)
Location: fs/debugfs/file.c:199
Inline: False
```
**Symbols:**

```
ffffffff813a3580-ffffffff813a3604: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813d28a0)
Location: fs/debugfs/file.c:219
Inline: False
```
**Symbols:**

```
ffffffff813d28a0-ffffffff813d2924: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813ecf90)
Location: fs/debugfs/file.c:220
Inline: False
```
**Symbols:**

```
ffffffff813ecf90-ffffffff813ed014: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (0)
Location: fs/debugfs/file.c:220
Inline: False
```
**Symbols:**

```
ffffffff81419150-ffffffff814191cd: full_proxy_read (STB_LOCAL)
ffffffff81419736-ffffffff81419748: full_proxy_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81433020)
Location: fs/debugfs/file.c:223
Inline: False
```
**Symbols:**

```
ffffffff81433020-ffffffff814330a4: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81482ba0)
Location: fs/debugfs/file.c:229
Inline: False
```
**Symbols:**

```
ffffffff81482ba0-ffffffff81482c1f: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a0230)
Location: fs/debugfs/file.c:229
Inline: False
```
**Symbols:**

```
ffffffff814a0230-ffffffff814a02af: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a6300)
Location: fs/debugfs/file.c:229
Inline: False
```
**Symbols:**

```
ffffffff814a6300-ffffffff814a637f: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814fdf70)
Location: fs/debugfs/file.c:231
Inline: False
```
**Symbols:**

```
ffffffff814fdf70-ffffffff814fdfef: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8158eba0)
Location: fs/debugfs/file.c:231
Inline: False
```
**Symbols:**

```
ffffffff8158eba0-ffffffff8158ec2c: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81635c70)
Location: fs/debugfs/file.c:231
Inline: False
```
**Symbols:**

```
ffffffff81635c70-ffffffff81635cfc: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8166dfa0)
Location: fs/debugfs/file.c:231
Inline: False
```
**Symbols:**

```
ffffffff8166dfa0-ffffffff8166e032: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff816a8780)
Location: fs/debugfs/file.c:323
Inline: False
```
**Symbols:**

```
ffffffff816a8780-ffffffff816a8815: full_proxy_read (STB_LOCAL)
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
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffff800010518880)
Location: fs/debugfs/file.c:223
Inline: False
```
**Symbols:**

```
ffff800010518880-ffff800010518914: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c06d2fa0)
Location: fs/debugfs/file.c:223
Inline: False
```
**Symbols:**

```
c06d2fa0-c06d3020: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c000000000661ac0)
Location: fs/debugfs/file.c:223
Inline: False
```
**Symbols:**

```
c000000000661ac0-c000000000661bd0: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffe000381d02)
Location: fs/debugfs/file.c:223
Inline: False
```
**Symbols:**

```
ffffffe000381d02-ffffffe000381d9a: full_proxy_read (STB_LOCAL)
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
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8142b600)
Location: fs/debugfs/file.c:223
Inline: False
```
**Symbols:**

```
ffffffff8142b600-ffffffff8142b684: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8141c080)
Location: fs/debugfs/file.c:223
Inline: False
```
**Symbols:**

```
ffffffff8141c080-ffffffff8141c104: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814277a0)
Location: fs/debugfs/file.c:223
Inline: False
```
**Symbols:**

```
ffffffff814277a0-ffffffff81427824: full_proxy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t full_proxy_read(struct file *filp, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8143e660)
Location: fs/debugfs/file.c:223
Inline: False
```
**Symbols:**

```
ffffffff8143e660-ffffffff8143e6e4: full_proxy_read (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
