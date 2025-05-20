# Function: <code>klist_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff818174a0)
Location: lib/klist.c:184
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_put
  - lib/klist.c:klist_prev
```
**Symbols:**

```
ffffffff818174a0-ffffffff8181758e: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81890f60)
Location: lib/klist.c:184
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff81890f60-ffffffff81891040: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff818c56f0)
Location: lib/klist.c:184
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff818c56f0-ffffffff818c57d0: klist_release (STB_LOCAL)
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
In lib/klist.c (ffffffff818ed7b4)
Location: lib/klist.c:184
Inline: True
Inline callers:
  - lib/klist.c:klist_dec_and_del
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81973920)
Location: lib/klist.c:184
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff81973920-ffffffff819739f3: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff819cfff0)
Location: lib/klist.c:184
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff819cfff0-ffffffff819d00c3: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a09340)
Location: lib/klist.c:184
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff81a09340-ffffffff81a09413: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/klist.c (0)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff81a78ce0-ffffffff81a78db9: klist_release (STB_LOCAL)
ffffffff81a7933e-ffffffff81a79351: klist_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81ab0090)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff81ab0090-ffffffff81ab0170: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff815ea270)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff815ea270-ffffffff815ea350: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff8160ebb0)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff8160ebb0-ffffffff8160ec90: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff815f2340)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff815f2340-ffffffff815f2420: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff8165f530)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff8165f530-ffffffff8165f610: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81778c70)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff81778c70-ffffffff81778d5f: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff82021a70)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff82021a70-ffffffff82021b5f: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff820a1ab0)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff820a1ab0-ffffffff820a1b9f: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff82179b30)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff82179b30-ffffffff82179c1f: klist_release (STB_LOCAL)
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
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffff800010d89aa8)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffff800010d89aa8-ffff800010d89bec: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (c0e84588)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
c0e84588-c0e84694: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (c000000000eca890)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
c000000000eca890-c000000000ecaa20: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffe0008b33a8)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffe0008b33a8-ffffffe0008b34b2: klist_release (STB_LOCAL)
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
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a4eee0)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff81a4eee0-ffffffff81a4efc0: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81a0bfe0)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff81a0bfe0-ffffffff81a0c0c0: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81abb2d0)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff81abb2d0-ffffffff81abb3b0: klist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void klist_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/klist.c (ffffffff81ac7730)
Location: lib/klist.c:183
Inline: False
Direct callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff81ac7730-ffffffff81ac7813: klist_release (STB_LOCAL)
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
