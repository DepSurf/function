# Function: <code>legitimize_links</code>

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
In fs/namei.c (ffffffff812174dd)
Location: fs/namei.c:642
Inline: True
Inline callers:
  - fs/namei.c:unlazy_walk
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
In fs/namei.c (ffffffff8123e71d)
Location: fs/namei.c:647
Inline: True
Inline callers:
  - fs/namei.c:unlazy_walk
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
In fs/namei.c (ffffffff812514ed)
Location: fs/namei.c:647
Inline: True
Inline callers:
  - fs/namei.c:unlazy_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125d1b0)
Location: fs/namei.c:647
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff8125d1b0-ffffffff8125d261: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127f530)
Location: fs/namei.c:648
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff8127f530-ffffffff8127f5e4: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a59c0)
Location: fs/namei.c:632
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff812a59c0-ffffffff812a5a78: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bab20)
Location: fs/namei.c:632
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff812bab20-ffffffff812babe3: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d7b00)
Location: fs/namei.c:630
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff812d7b00-ffffffff812d7bc3: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9660)
Location: fs/namei.c:628
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff812e9660-ffffffff812e9723: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81320f00)
Location: fs/namei.c:630
Inline: False
Direct callers:
  - fs/namei.c:unlazy_child
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff81320f00-ffffffff81320fb4: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132c490)
Location: fs/namei.c:630
Inline: False
Direct callers:
  - fs/namei.c:unlazy_child
  - fs/namei.c:try_to_unlazy
```
**Symbols:**

```
ffffffff8132c490-ffffffff8132c544: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81332fb0)
Location: fs/namei.c:684
Inline: True
Direct callers:
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
```
**Symbols:**

```
ffffffff81332fb0-ffffffff813330c0: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813808e0)
Location: fs/namei.c:711
Inline: True
Direct callers:
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
```
**Symbols:**

```
ffffffff813808e0-ffffffff813809f0: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81400c80)
Location: fs/namei.c:712
Inline: False
Direct callers:
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
```
**Symbols:**

```
ffffffff81400c80-ffffffff81400d7b: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148abc0)
Location: fs/namei.c:718
Inline: False
Direct callers:
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
```
**Symbols:**

```
ffffffff8148abc0-ffffffff8148acbb: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c12d0)
Location: fs/namei.c:721
Inline: False
Direct callers:
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
```
**Symbols:**

```
ffffffff814c12d0-ffffffff814c13cb: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f3790)
Location: fs/namei.c:724
Inline: False
Direct callers:
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
```
**Symbols:**

```
ffffffff814f3790-ffffffff814f388b: legitimize_links (STB_LOCAL)
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
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010392a80)
Location: fs/namei.c:628
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffff800010392a80-ffff800010392b54: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c05791e4)
Location: fs/namei.c:628
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
c05791e4-c05792a0: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048bd30)
Location: fs/namei.c:628
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
c00000000048bd30-c00000000048be78: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000261bf6)
Location: fs/namei.c:628
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffe000261bf6-ffffffe000261c98: legitimize_links (STB_LOCAL)
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
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e1c40)
Location: fs/namei.c:628
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff812e1c40-ffffffff812e1d03: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d2880)
Location: fs/namei.c:628
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff812d2880-ffffffff812d2943: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dfa50)
Location: fs/namei.c:628
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff812dfa50-ffffffff812dfb13: legitimize_links (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f1100)
Location: fs/namei.c:628
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:unlazy_walk
```
**Symbols:**

```
ffffffff812f1100-ffffffff812f11c3: legitimize_links (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
