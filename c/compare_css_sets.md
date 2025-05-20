# Function: <code>compare_css_sets</code>

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
In kernel/cgroup.c (ffffffff8111579b)
Location: kernel/cgroup.c:828
Inline: True
Inline callers:
  - kernel/cgroup.c:find_css_set
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
In kernel/cgroup.c (ffffffff8111c460)
Location: kernel/cgroup.c:873
Inline: True
Inline callers:
  - kernel/cgroup.c:find_css_set
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
In kernel/cgroup.c (ffffffff81124790)
Location: kernel/cgroup.c:876
Inline: True
Inline callers:
  - kernel/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff81123b4a)
Location: kernel/cgroup/cgroup.c:769
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff8112ffee)
Location: kernel/cgroup/cgroup.c:903
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff8113e6bd)
Location: kernel/cgroup/cgroup.c:906
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff8114a0e6)
Location: kernel/cgroup/cgroup.c:941
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff81155507)
Location: kernel/cgroup/cgroup.c:981
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff81161110)
Location: kernel/cgroup/cgroup.c:981
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool compare_css_sets(struct css_set *cset, struct css_set *old_cset, struct cgroup *new_cgrp, struct cgroup_subsys_state **template);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116ecd0)
Location: kernel/cgroup/cgroup.c:973
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:find_existing_css_set
```
**Symbols:**

```
ffffffff8116ecd0-ffffffff8116edab: compare_css_sets (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool compare_css_sets(struct css_set *cset, struct css_set *old_cset, struct cgroup *new_cgrp, struct cgroup_subsys_state **template);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116b700)
Location: kernel/cgroup/cgroup.c:970
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:find_existing_css_set
```
**Symbols:**

```
ffffffff8116b700-ffffffff8116b7db: compare_css_sets (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (ffffffff8116cce6)
Location: kernel/cgroup/cgroup.c:970
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_existing_css_set
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
In kernel/cgroup/cgroup.c (ffffffff81192985)
Location: kernel/cgroup/cgroup.c:1001
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_existing_css_set
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
In kernel/cgroup/cgroup.c (ffffffff811c2fcb)
Location: kernel/cgroup/cgroup.c:1003
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_existing_css_set
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
In kernel/cgroup/cgroup.c (ffffffff8120519a)
Location: kernel/cgroup/cgroup.c:1008
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_existing_css_set
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
In kernel/cgroup/cgroup.c (ffffffff8121aa6a)
Location: kernel/cgroup/cgroup.c:992
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_existing_css_set
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
In kernel/cgroup/cgroup.c (ffffffff812327da)
Location: kernel/cgroup/cgroup.c:972
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_existing_css_set
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
In kernel/cgroup/cgroup.c (ffff8000101d2514)
Location: kernel/cgroup/cgroup.c:981
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (c041536c)
Location: kernel/cgroup/cgroup.c:981
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (c00000000023d144)
Location: kernel/cgroup/cgroup.c:981
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffe00014bda4)
Location: kernel/cgroup/cgroup.c:981
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff81159730)
Location: kernel/cgroup/cgroup.c:981
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff8114ca40)
Location: kernel/cgroup/cgroup.c:981
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff81157500)
Location: kernel/cgroup/cgroup.c:981
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
In kernel/cgroup/cgroup.c (ffffffff81164560)
Location: kernel/cgroup/cgroup.c:981
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
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
