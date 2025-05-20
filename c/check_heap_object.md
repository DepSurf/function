# Function: <code>check_heap_object</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff8122e649)
Location: mm/usercopy.c:201
Inline: True
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
In mm/usercopy.c (ffffffff81240b79)
Location: mm/usercopy.c:201
Inline: True
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
In mm/usercopy.c (ffffffff8124c888)
Location: mm/usercopy.c:198
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
In mm/usercopy.c (ffffffff8126cd48)
Location: mm/usercopy.c:198
Inline: True
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
In mm/usercopy.c (ffffffff812919a6)
Location: mm/usercopy.c:224
Inline: True
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
In mm/usercopy.c (ffffffff812a69e0)
Location: mm/usercopy.c:226
Inline: True
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
In mm/usercopy.c (ffffffff812c20c5)
Location: mm/usercopy.c:222
Inline: True
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
In mm/usercopy.c (ffffffff812d3ff5)
Location: mm/usercopy.c:223
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff81309d52)
Location: mm/usercopy.c:223
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff81315b72)
Location: mm/usercopy.c:223
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff8131bd62)
Location: mm/usercopy.c:223
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff81369042)
Location: mm/usercopy.c:223
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void check_heap_object(const void *ptr, long unsigned int n, bool to_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/usercopy.c (0)
Location: mm/usercopy.c:161
Inline: False
```
**Symbols:**

```
ffffffff813e6c00-ffffffff813e6ddd: check_heap_object (STB_LOCAL)
ffffffff81e75cab-ffffffff81e75d14: check_heap_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void check_heap_object(const void *ptr, long unsigned int n, bool to_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/usercopy.c (0)
Location: mm/usercopy.c:162
Inline: False
```
**Symbols:**

```
ffffffff8146e7c0-ffffffff8146e96f: check_heap_object (STB_LOCAL)
ffffffff820685cb-ffffffff820685e5: check_heap_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void check_heap_object(const void *ptr, long unsigned int n, bool to_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/usercopy.c (0)
Location: mm/usercopy.c:162
Inline: False
```
**Symbols:**

```
ffffffff814a2f60-ffffffff814a312e: check_heap_object (STB_LOCAL)
ffffffff820e7ea0-ffffffff820e7ebb: check_heap_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void check_heap_object(const void *ptr, long unsigned int n, bool to_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/usercopy.c (0)
Location: mm/usercopy.c:162
Inline: False
```
**Symbols:**

```
ffffffff814d3df0-ffffffff814d3fc1: check_heap_object (STB_LOCAL)
ffffffff821c4be2-ffffffff821c4bfa: check_heap_object.cold (STB_LOCAL)
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
In mm/usercopy.c (ffff800010379fbc)
Location: mm/usercopy.c:223
Inline: True
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
In mm/usercopy.c (c05651d4)
Location: mm/usercopy.c:223
Inline: True
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
In mm/usercopy.c (c00000000046d3e0)
Location: mm/usercopy.c:223
Inline: True
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
In mm/usercopy.c (ffffffe000251222)
Location: mm/usercopy.c:223
Inline: True
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
In mm/usercopy.c (ffffffff812cc5d5)
Location: mm/usercopy.c:223
Inline: True
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
In mm/usercopy.c (ffffffff812bd445)
Location: mm/usercopy.c:223
Inline: True
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
In mm/usercopy.c (ffffffff812ca3e5)
Location: mm/usercopy.c:223
Inline: True
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
In mm/usercopy.c (ffffffff812db0e5)
Location: mm/usercopy.c:223
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
