# Function: <code>nd_alloc_stack</code>

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
In fs/namei.c (ffffffff812189c3)
Location: fs/namei.c:581
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (ffffffff8123f6b3)
Location: fs/namei.c:589
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (ffffffff81252483)
Location: fs/namei.c:589
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (ffffffff8125e7c9)
Location: fs/namei.c:589
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (ffffffff812809e9)
Location: fs/namei.c:590
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (ffffffff812a694a)
Location: fs/namei.c:574
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (ffffffff812bbb7a)
Location: fs/namei.c:574
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (ffffffff812d872a)
Location: fs/namei.c:572
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (ffffffff812ea23a)
Location: fs/namei.c:572
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool nd_alloc_stack(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81321920)
Location: fs/namei.c:548
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff81321920-ffffffff813219ec: nd_alloc_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool nd_alloc_stack(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132cec0)
Location: fs/namei.c:548
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff8132cec0-ffffffff8132cf8c: nd_alloc_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool nd_alloc_stack(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81332b00)
Location: fs/namei.c:600
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff81332b00-ffffffff81332bcc: nd_alloc_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool nd_alloc_stack(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81380290)
Location: fs/namei.c:627
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff81380290-ffffffff8138035c: nd_alloc_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool nd_alloc_stack(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814001d0)
Location: fs/namei.c:628
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff814001d0-ffffffff814002b4: nd_alloc_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool nd_alloc_stack(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148a230)
Location: fs/namei.c:628
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff8148a230-ffffffff8148a317: nd_alloc_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool nd_alloc_stack(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814bf550)
Location: fs/namei.c:631
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff814bf550-ffffffff814bf637: nd_alloc_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool nd_alloc_stack(struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f1a10)
Location: fs/namei.c:632
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff814f1a10-ffffffff814f1b26: nd_alloc_stack (STB_LOCAL)
```
</details>
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
In fs/namei.c (ffff8000103936cc)
Location: fs/namei.c:572
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (c057b100)
Location: fs/namei.c:572
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (c00000000048dac4)
Location: fs/namei.c:572
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (ffffffe0002625a4)
Location: fs/namei.c:572
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (ffffffff812e281a)
Location: fs/namei.c:572
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (ffffffff812d345a)
Location: fs/namei.c:572
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (ffffffff812e062a)
Location: fs/namei.c:572
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
In fs/namei.c (ffffffff812f271a)
Location: fs/namei.c:572
Inline: True
Inline callers:
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
  - fs/namei.c:pick_link
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
