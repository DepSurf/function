# Function: <code>proc_setup_self</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff81283bd0)
Location: fs/proc/self.c:45
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff81283bd0-ffffffff81283cec: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff812b0c50)
Location: fs/proc/self.c:47
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff812b0c50-ffffffff812b0d64: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff812c65b0)
Location: fs/proc/self.c:34
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff812c65b0-ffffffff812c66b8: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff812d37b0)
Location: fs/proc/self.c:34
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff812d37b0-ffffffff812d38b6: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff812f7fe0)
Location: fs/proc/self.c:35
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff812f7fe0-ffffffff812f80e3: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/self.c (0)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff81325402-ffffffff81325416: proc_setup_self.cold.3 (STB_LOCAL)
ffffffff81325310-ffffffff81325402: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/self.c (0)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/inode.c:proc_fill_super
```
**Symbols:**

```
ffffffff8133c5a2-ffffffff8133c5b6: proc_setup_self.cold.3 (STB_LOCAL)
ffffffff8133c4b0-ffffffff8133c5a2: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff81364710)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff81364710-ffffffff81364807: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff8137c9a0)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff8137c9a0-ffffffff8137ca97: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff813c6330)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff813c6330-ffffffff813c6423: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff813d82e0)
Location: fs/proc/self.c:43
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff813d82e0-ffffffff813d83d3: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff813df180)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff813df180-ffffffff813df273: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff81430b30)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff81430b30-ffffffff81430c23: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff814aa880)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff814aa880-ffffffff814aa97f: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff815404f0)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff815404f0-ffffffff81540600: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff815788b0)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff815788b0-ffffffff815789c0: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff815b1040)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff815b1040-ffffffff815b1131: proc_setup_self (STB_GLOBAL)
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
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffff800010449300)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffff800010449300-ffff8000104493f0: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (c060e3c0)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
c060e3c0-c060e4f4: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (c00000000055fdf0)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
c00000000055fdf0-c00000000055ff34: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffe0002deca6)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffe0002deca6-ffffffe0002ded92: proc_setup_self (STB_GLOBAL)
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
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff81374f80)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff81374f80-ffffffff81375077: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff81365a50)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff81365a50-ffffffff81365b47: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff81372a50)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff81372a50-ffffffff81372b47: proc_setup_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int proc_setup_self(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/self.c (ffffffff81386430)
Location: fs/proc/self.c:36
Inline: False
Direct callers:
  - fs/proc/root.c:proc_fill_super
```
**Symbols:**

```
ffffffff81386430-ffffffff81386527: proc_setup_self (STB_GLOBAL)
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
