# Function: <code>cgroup_destroy_root</code>

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
In kernel/cgroup.c (ffffffff81115550)
Location: kernel/cgroup.c:1135
Inline: True
Inline callers:
  - kernel/cgroup.c:css_free_work_fn
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
In kernel/cgroup.c (ffffffff8111f1db)
Location: kernel/cgroup.c:1174
Inline: True
Inline callers:
  - kernel/cgroup.c:css_free_work_fn
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
In kernel/cgroup.c (ffffffff8112756b)
Location: kernel/cgroup.c:1177
Inline: True
Inline callers:
  - kernel/cgroup.c:css_free_work_fn
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
In kernel/cgroup/cgroup.c (ffffffff811277e6)
Location: kernel/cgroup/cgroup.c:1070
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_work_fn
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
In kernel/cgroup/cgroup.c (ffffffff81133be2)
Location: kernel/cgroup/cgroup.c:1239
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_work_fn
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
In kernel/cgroup/cgroup.c (ffffffff81142285)
Location: kernel/cgroup/cgroup.c:1242
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffff8114dd0d)
Location: kernel/cgroup/cgroup.c:1277
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffff81159acc)
Location: kernel/cgroup/cgroup.c:1318
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffff8116573d)
Location: kernel/cgroup/cgroup.c:1318
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_destroy_root(struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81176700)
Location: kernel/cgroup/cgroup.c:1307
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff81176700-ffffffff811768d3: cgroup_destroy_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_destroy_root(struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811733f0)
Location: kernel/cgroup/cgroup.c:1304
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff811733f0-ffffffff811735b4: cgroup_destroy_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_destroy_root(struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173fc0)
Location: kernel/cgroup/cgroup.c:1304
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff81173fc0-ffffffff8117419d: cgroup_destroy_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cgroup_destroy_root(struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119b050)
Location: kernel/cgroup/cgroup.c:1335
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff8119b050-ffffffff8119b22d: cgroup_destroy_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cgroup_destroy_root(struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cb200)
Location: kernel/cgroup/cgroup.c:1338
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff811cb200-ffffffff811cb3e9: cgroup_destroy_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cgroup_destroy_root(struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120e640)
Location: kernel/cgroup/cgroup.c:1357
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff8120e640-ffffffff8120e833: cgroup_destroy_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cgroup_destroy_root(struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81224040)
Location: kernel/cgroup/cgroup.c:1341
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff81224040-ffffffff81224233: cgroup_destroy_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cgroup_destroy_root(struct cgroup_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:1321
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff8123bd20-ffffffff8123bf2e: cgroup_destroy_root (STB_LOCAL)
ffffffff821b67a2-ffffffff821b67b7: cgroup_destroy_root.cold (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (ffff8000101d7220)
Location: kernel/cgroup/cgroup.c:1318
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (c0419ec0)
Location: kernel/cgroup/cgroup.c:1318
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (c000000000243870)
Location: kernel/cgroup/cgroup.c:1318
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffe000150324)
Location: kernel/cgroup/cgroup.c:1318
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffff8115dd5d)
Location: kernel/cgroup/cgroup.c:1318
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffff8115103d)
Location: kernel/cgroup/cgroup.c:1318
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffff8115bb2d)
Location: kernel/cgroup/cgroup.c:1318
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffff81168c12)
Location: kernel/cgroup/cgroup.c:1318
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
