# Function: <code>legitimize_root</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
bool legitimize_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9730)
Location: fs/namei.c:642
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff812e9730-ffffffff812e9772: legitimize_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool legitimize_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81320fc0)
Location: fs/namei.c:644
Inline: False
Direct callers:
  - fs/namei.c:unlazy_child
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff81320fc0-ffffffff81321002: legitimize_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool legitimize_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132c550)
Location: fs/namei.c:644
Inline: False
Direct callers:
  - fs/namei.c:unlazy_child
  - fs/namei.c:try_to_unlazy
```
**Symbols:**

```
ffffffff8132c550-ffffffff8132c592: legitimize_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool legitimize_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813324d0)
Location: fs/namei.c:703
Inline: False
Direct callers:
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
```
**Symbols:**

```
ffffffff813324d0-ffffffff81332512: legitimize_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool legitimize_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8137fc60)
Location: fs/namei.c:730
Inline: False
Direct callers:
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
```
**Symbols:**

```
ffffffff8137fc60-ffffffff8137fca3: legitimize_root (STB_LOCAL)
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
In fs/namei.c (ffffffff81400f82)
Location: fs/namei.c:731
Inline: True
Inline callers:
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
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
In fs/namei.c (ffffffff8148ad3a)
Location: fs/namei.c:737
Inline: True
Inline callers:
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
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
In fs/namei.c (ffffffff814c144a)
Location: fs/namei.c:740
Inline: True
Inline callers:
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f390a)
Location: fs/namei.c:743
Inline: True
Inline callers:
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
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
bool legitimize_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010392b58)
Location: fs/namei.c:642
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffff800010392b58-ffff800010392bcc: legitimize_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool legitimize_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c05792a0)
Location: fs/namei.c:642
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
c05792a0-c05792ec: legitimize_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool legitimize_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048be80)
Location: fs/namei.c:642
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
c00000000048be80-c00000000048bedc: legitimize_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool legitimize_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000261c98)
Location: fs/namei.c:642
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffe000261c98-ffffffe000261cfa: legitimize_root (STB_LOCAL)
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
bool legitimize_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e1d10)
Location: fs/namei.c:642
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff812e1d10-ffffffff812e1d52: legitimize_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool legitimize_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d2950)
Location: fs/namei.c:642
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff812d2950-ffffffff812d2992: legitimize_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool legitimize_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dfb20)
Location: fs/namei.c:642
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff812dfb20-ffffffff812dfb62: legitimize_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool legitimize_root(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f11d0)
Location: fs/namei.c:642
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff812f11d0-ffffffff812f1212: legitimize_root (STB_LOCAL)
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
