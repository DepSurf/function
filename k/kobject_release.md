# Function: <code>kobject_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kobject_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813eb8b0)
Location: lib/kobject.c:663
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff813eb8b0-ffffffff813eba3e: kobject_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kobject_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81431ca0)
Location: lib/kobject.c:663
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff81431ca0-ffffffff81431e0d: kobject_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kobject_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144df10)
Location: lib/kobject.c:663
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff8144df10-ffffffff8144e07d: kobject_release (STB_LOCAL)
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
In lib/kobject.c (ffffffff818ee110)
Location: lib/kobject.c:666
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kobject_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819743f0)
Location: lib/kobject.c:666
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff819743f0-ffffffff81974561: kobject_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kobject_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d0910)
Location: lib/kobject.c:680
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff819d0910-ffffffff819d0a8d: kobject_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kobject_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a09f30)
Location: lib/kobject.c:680
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff81a09f30-ffffffff81a0a0ad: kobject_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kobject_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a79780)
Location: lib/kobject.c:711
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff81a79780-ffffffff81a798f8: kobject_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kobject_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab0ae0)
Location: lib/kobject.c:711
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff81ab0ae0-ffffffff81ab0c58: kobject_release (STB_LOCAL)
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
In lib/kobject.c (ffffffff815eaecb)
Location: lib/kobject.c:728
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In lib/kobject.c (ffffffff8160f7eb)
Location: lib/kobject.c:725
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In lib/kobject.c (ffffffff815f2f2b)
Location: lib/kobject.c:725
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In lib/kobject.c (ffffffff816600fb)
Location: lib/kobject.c:725
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In lib/kobject.c (ffffffff81779c1f)
Location: lib/kobject.c:693
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In lib/kobject.c (ffffffff82022c1f)
Location: lib/kobject.c:701
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In lib/kobject.c (ffffffff820a2c8f)
Location: lib/kobject.c:702
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In lib/kobject.c (ffffffff8217ad0f)
Location: lib/kobject.c:709
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In lib/kobject.c (ffff800010d8ab90)
Location: lib/kobject.c:711
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In lib/kobject.c (c0e8504c)
Location: lib/kobject.c:711
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In lib/kobject.c (c000000000ecb8b0)
Location: lib/kobject.c:711
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In lib/kobject.c (ffffffe0008b4118)
Location: lib/kobject.c:711
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
void kobject_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a4f930)
Location: lib/kobject.c:711
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff81a4f930-ffffffff81a4faa8: kobject_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kobject_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0ca30)
Location: lib/kobject.c:711
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff81a0ca30-ffffffff81a0cba8: kobject_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kobject_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abbd20)
Location: lib/kobject.c:711
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff81abbd20-ffffffff81abbe98: kobject_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kobject_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac81b0)
Location: lib/kobject.c:711
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff81ac81b0-ffffffff81ac8328: kobject_release (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
