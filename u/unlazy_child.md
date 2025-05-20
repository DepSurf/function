# Function: <code>unlazy_child</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125df3d)
Location: fs/namei.c:726
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
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
In fs/namei.c (ffffffff812802b3)
Location: fs/namei.c:727
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a679c)
Location: fs/namei.c:711
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bb86c)
Location: fs/namei.c:711
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
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
In fs/namei.c (ffffffff812d8547)
Location: fs/namei.c:709
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
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
In fs/namei.c (ffffffff812ea0b7)
Location: fs/namei.c:710
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unlazy_child(struct nameidata *nd, struct dentry *dentry, unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81321090)
Location: fs/namei.c:720
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff81321090-ffffffff81321141: unlazy_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unlazy_child(struct nameidata *nd, struct dentry *dentry, unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132c630)
Location: fs/namei.c:720
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff8132c630-ffffffff8132c6f0: unlazy_child (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
In fs/namei.c (ffff80001039354c)
Location: fs/namei.c:710
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
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
In fs/namei.c (c057a604)
Location: fs/namei.c:710
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
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
In fs/namei.c (c00000000048ce7c)
Location: fs/namei.c:710
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
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
In fs/namei.c (ffffffe00026248e)
Location: fs/namei.c:710
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
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
In fs/namei.c (ffffffff812e2697)
Location: fs/namei.c:710
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
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
In fs/namei.c (ffffffff812d32d7)
Location: fs/namei.c:710
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
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
In fs/namei.c (ffffffff812e04a7)
Location: fs/namei.c:710
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
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
In fs/namei.c (ffffffff812f1d87)
Location: fs/namei.c:710
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
