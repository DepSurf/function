# Function: <code>pid_revalidate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8127c550)
Location: fs/proc/base.c:1735
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff8127c550-ffffffff8127c62d: pid_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812a91e0)
Location: fs/proc/base.c:1751
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff812a91e0-ffffffff812a92e3: pid_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812beae0)
Location: fs/proc/base.c:1771
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff812beae0-ffffffff812bebe3: pid_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812cd0d0)
Location: fs/proc/base.c:1822
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff812cd0d0-ffffffff812cd154: pid_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812f1970)
Location: fs/proc/base.c:1823
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
```
**Symbols:**

```
ffffffff812f1970-ffffffff812f19f4: pid_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131ec50)
Location: fs/proc/base.c:1802
Inline: False
```
**Symbols:**

```
ffffffff8131ec50-ffffffff8131ecbb: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81335d40)
Location: fs/proc/base.c:1816
Inline: False
```
**Symbols:**

```
ffffffff81335d40-ffffffff81335dab: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135dde0)
Location: fs/proc/base.c:1829
Inline: False
```
**Symbols:**

```
ffffffff8135dde0-ffffffff8135de55: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81376040)
Location: fs/proc/base.c:1829
Inline: False
```
**Symbols:**

```
ffffffff81376040-ffffffff813760b5: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813be850)
Location: fs/proc/base.c:1962
Inline: False
```
**Symbols:**

```
ffffffff813be850-ffffffff813be903: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d0620)
Location: fs/proc/base.c:1976
Inline: False
```
**Symbols:**

```
ffffffff813d0620-ffffffff813d06d3: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d7520)
Location: fs/proc/base.c:1975
Inline: False
```
**Symbols:**

```
ffffffff813d7520-ffffffff813d75d3: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81428c60)
Location: fs/proc/base.c:1981
Inline: False
```
**Symbols:**

```
ffffffff81428c60-ffffffff81428d13: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff814a1f80)
Location: fs/proc/base.c:2008
Inline: False
```
**Symbols:**

```
ffffffff814a1f80-ffffffff814a200a: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81537060)
Location: fs/proc/base.c:2009
Inline: False
```
**Symbols:**

```
ffffffff81537060-ffffffff815370ea: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156f250)
Location: fs/proc/base.c:2009
Inline: False
```
**Symbols:**

```
ffffffff8156f250-ffffffff8156f2da: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a7c20)
Location: fs/proc/base.c:2003
Inline: False
```
**Symbols:**

```
ffffffff815a7c20-ffffffff815a7caa: pid_revalidate (STB_LOCAL)
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
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff800010441478)
Location: fs/proc/base.c:1829
Inline: False
```
**Symbols:**

```
ffff800010441478-ffff80001044150c: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0606dd0)
Location: fs/proc/base.c:1829
Inline: False
```
**Symbols:**

```
c0606dd0-c0606e40: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000556610)
Location: fs/proc/base.c:1829
Inline: False
```
**Symbols:**

```
c000000000556610-c0000000005566e8: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d8390)
Location: fs/proc/base.c:1829
Inline: False
```
**Symbols:**

```
ffffffe0002d8390-ffffffe0002d8418: pid_revalidate (STB_LOCAL)
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
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136e620)
Location: fs/proc/base.c:1829
Inline: False
```
**Symbols:**

```
ffffffff8136e620-ffffffff8136e695: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135f0b0)
Location: fs/proc/base.c:1829
Inline: False
```
**Symbols:**

```
ffffffff8135f0b0-ffffffff8135f125: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136c0f0)
Location: fs/proc/base.c:1829
Inline: False
```
**Symbols:**

```
ffffffff8136c0f0-ffffffff8136c165: pid_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pid_revalidate(struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8137f9b0)
Location: fs/proc/base.c:1829
Inline: False
```
**Symbols:**

```
ffffffff8137f9b0-ffffffff8137fa25: pid_revalidate (STB_LOCAL)
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
