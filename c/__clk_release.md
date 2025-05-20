# Function: <code>__clk_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e50a0)
Location: drivers/clk/clk.c:2599
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_put
```
**Symbols:**

```
ffffffff816e50a0-ffffffff816e5115: __clk_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81749830)
Location: drivers/clk/clk.c:2633
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff81749830-ffffffff817498a5: __clk_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815320b0)
Location: drivers/clk/clk.c:2636
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff815320b0-ffffffff81532125: __clk_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815452e0)
Location: drivers/clk/clk.c:2670
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
```
**Symbols:**

```
ffffffff815452e0-ffffffff81545372: __clk_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a8530)
Location: drivers/clk/clk.c:2810
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
```
**Symbols:**

```
ffffffff815a8530-ffffffff815a85c2: __clk_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e0210)
Location: drivers/clk/clk.c:3068
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff815e0210-ffffffff815e02a0: __clk_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fa1b0)
Location: drivers/clk/clk.c:3369
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff815fa1b0-ffffffff815fa240: __clk_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162dde0)
Location: drivers/clk/clk.c:3717
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff8162dde0-ffffffff8162de1b: __clk_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164faf0)
Location: drivers/clk/clk.c:3797
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff8164faf0-ffffffff8164fb2b: __clk_release (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff817027b3)
Location: drivers/clk/clk.c:3887
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
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
In drivers/clk/clk.c (ffffffff8171fa93)
Location: drivers/clk/clk.c:3956
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
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
In drivers/clk/clk.c (ffffffff81700ce3)
Location: drivers/clk/clk.c:3965
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
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
In drivers/clk/clk.c (ffffffff8177b4f3)
Location: drivers/clk/clk.c:3992
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
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
In drivers/clk/clk.c (ffffffff818b1d58)
Location: drivers/clk/clk.c:4065
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
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
In drivers/clk/clk.c (ffffffff819fe38b)
Location: drivers/clk/clk.c:4254
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
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
In drivers/clk/clk.c (ffffffff81a4700b)
Location: drivers/clk/clk.c:4306
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
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
In drivers/clk/clk.c (ffffffff81a92aab)
Location: drivers/clk/clk.c:4352
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
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
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bea88)
Location: drivers/clk/clk.c:3797
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffff8000107bea88-ffff8000107beacc: __clk_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e8c58)
Location: drivers/clk/clk.c:3797
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
c08e8c58-c08e8c90: __clk_release (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050deb2)
Location: drivers/clk/clk.c:3797
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffe00050deb2-ffffffe00050defa: __clk_release (STB_LOCAL)
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
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81615b50)
Location: drivers/clk/clk.c:3797
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff81615b50-ffffffff81615b8b: __clk_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8160a080)
Location: drivers/clk/clk.c:3797
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff8160a080-ffffffff8160a0bb: __clk_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81643930)
Location: drivers/clk/clk.c:3797
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff81643930-ffffffff8164396b: __clk_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __clk_release(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165dd70)
Location: drivers/clk/clk.c:3797
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff8165dd70-ffffffff8165ddab: __clk_release (STB_LOCAL)
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
