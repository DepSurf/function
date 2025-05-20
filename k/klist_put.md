# Function: <code>klist_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81817840)
Location: lib/klist.c:210
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff81817840-ffffffff818178be: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff818912f0)
Location: lib/klist.c:210
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff818912f0-ffffffff81891369: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff818c5a80)
Location: lib/klist.c:210
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff818c5a80-ffffffff818c5af9: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff818ed880)
Location: lib/klist.c:210
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff818ed880-ffffffff818ed8ee: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81973ce0)
Location: lib/klist.c:210
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff81973ce0-ffffffff81973d5c: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff819d01d0)
Location: lib/klist.c:210
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff819d01d0-ffffffff819d024c: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a09730)
Location: lib/klist.c:210
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff81a09730-ffffffff81a097ac: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/klist.c (0)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff81a790a0-ffffffff81a79116: klist_put (STB_LOCAL)
ffffffff81a7936c-ffffffff81a7937f: klist_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81ab0440)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff81ab0440-ffffffff81ab04b8: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff815ea4a0)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff815ea4a0-ffffffff815ea52d: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff8160ede0)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff8160ede0-ffffffff8160ee6d: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff815f2570)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff815f2570-ffffffff815f25fd: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff8165f760)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff8165f760-ffffffff8165f7eb: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81778f30)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff81778f30-ffffffff81778fd8: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff82021d60)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff82021d60-ffffffff82021e08: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff820a1db0)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff820a1db0-ffffffff820a1e58: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff82179e30)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff82179e30-ffffffff82179ed8: klist_put (STB_LOCAL)
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
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffff800010d8a0f0)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffff800010d8a0f0-ffff800010d8a1d4: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (c0e84694)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
c0e84694-c0e84748: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (c000000000ecaa20)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
c000000000ecaa20-c000000000ecab48: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffe0008b38c6)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffe0008b38c6-ffffffe0008b397c: klist_put (STB_LOCAL)
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
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a4f290)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff81a4f290-ffffffff81a4f308: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a0c390)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff81a0c390-ffffffff81a0c408: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81abb680)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff81abb680-ffffffff81abb6f8: klist_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void klist_put(struct klist_node *n, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81ac7af0)
Location: lib/klist.c:209
Inline: False
Direct callers:
  - lib/klist.c:klist_iter_exit
  - lib/klist.c:klist_remove
```
**Symbols:**

```
ffffffff81ac7af0-ffffffff81ac7b72: klist_put (STB_LOCAL)
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
