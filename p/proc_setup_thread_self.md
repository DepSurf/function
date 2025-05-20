# Function: <code>proc_setup_thread_self</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff81283e50)
Location: fs/proc/thread_self.c:46
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff81283e50-ffffffff81283f6c: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff812b0f00)
Location: fs/proc/thread_self.c:49
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff812b0f00-ffffffff812b1014: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff812c67a0)
Location: fs/proc/thread_self.c:35
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff812c67a0-ffffffff812c68a8: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff812d39a0)
Location: fs/proc/thread_self.c:35
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff812d39a0-ffffffff812d3aa6: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff812f81d0)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff812f81d0-ffffffff812f82d3: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/thread_self.c (0)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff813255f2-ffffffff81325606: proc_setup_thread_self.cold.3 (STB_LOCAL)
ffffffff81325500-ffffffff813255f2: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/thread_self.c (0)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff8133c792-ffffffff8133c7a6: proc_setup_thread_self.cold.3 (STB_LOCAL)
ffffffff8133c6a0-ffffffff8133c792: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff813648f0)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff813648f0-ffffffff813649e7: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff8137cb80)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff8137cb80-ffffffff8137cc77: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff813c6510)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff813c6510-ffffffff813c6603: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff813d84d0)
Location: fs/proc/thread_self.c:43
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff813d84d0-ffffffff813d85c3: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff813df360)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff813df360-ffffffff813df453: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff81430d10)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff81430d10-ffffffff81430e03: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff814aaa70)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff814aaa70-ffffffff814aab6f: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff81540710)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff81540710-ffffffff81540820: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff81578ad0)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff81578ad0-ffffffff81578be0: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff815b12b0)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff815b12b0-ffffffff815b13a1: proc_setup_thread_self (STB_GLOBAL)
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
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffff8000104494d8)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffff8000104494d8-ffff8000104495c4: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (c060e5dc)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
c060e5dc-c060e710: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (c0000000005600a0)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
c0000000005600a0-c0000000005601e4: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffe0002dee54)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffe0002dee54-ffffffe0002def40: proc_setup_thread_self (STB_GLOBAL)
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
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff81375160)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff81375160-ffffffff81375257: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff81365c30)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff81365c30-ffffffff81365d27: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff81372c30)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff81372c30-ffffffff81372d27: proc_setup_thread_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int proc_setup_thread_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/thread_self.c (ffffffff81386610)
Location: fs/proc/thread_self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff81386610-ffffffff81386707: proc_setup_thread_self (STB_GLOBAL)
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
