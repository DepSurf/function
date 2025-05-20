# Function: <code>dentry_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812238f5)
Location: fs/dcache.c:558
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124bf87)
Location: fs/dcache.c:561
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125ef67)
Location: fs/dcache.c:561
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126c8f5)
Location: fs/dcache.c:595
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128ec45)
Location: fs/dcache.c:602
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b5c50)
Location: fs/dcache.c:651
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff812b5c50-ffffffff812b5de3: dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cb1d0)
Location: fs/dcache.c:664
Inline: False
Direct callers:
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff812cb1d0-ffffffff812cb363: dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e7993)
Location: fs/dcache.c:664
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f9530)
Location: fs/dcache.c:664
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813327f0)
Location: fs/dcache.c:683
Inline: False
Direct callers:
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff813327f0-ffffffff81332a4b: dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133ddf0)
Location: fs/dcache.c:683
Inline: False
Direct callers:
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff8133ddf0-ffffffff8133dfa3: dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813441e0)
Location: fs/dcache.c:686
Inline: False
Direct callers:
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff813441e0-ffffffff81344393: dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *dentry_kill(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81391cd0)
Location: fs/dcache.c:686
Inline: False
Direct callers:
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff81391cd0-ffffffff81391e83: dentry_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814139e4)
Location: fs/dcache.c:711
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149ede4)
Location: fs/dcache.c:711
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d4104)
Location: fs/dcache.c:711
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a7a0c)
Location: fs/dcache.c:664
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0589a38)
Location: fs/dcache.c:664
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a2b44)
Location: fs/dcache.c:664
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026e160)
Location: fs/dcache.c:664
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1b10)
Location: fs/dcache.c:664
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e2740)
Location: fs/dcache.c:664
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ef920)
Location: fs/dcache.c:664
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81300df2)
Location: fs/dcache.c:664
Inline: True
Inline callers:
  - fs/dcache.c:dput
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
</ul>
