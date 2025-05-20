# Function: <code>cgroup_idr_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cgroup_idr_remove(struct idr *idr, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81112a50)
Location: kernel/cgroup.c:337
Inline: False
Direct callers:
  - kernel/cgroup.c:css_release_work_fn
  - kernel/cgroup.c:create_css
  - kernel/cgroup.c:css_free_work_fn
```
**Symbols:**

```
ffffffff81112a50-ffffffff81112a8a: cgroup_idr_remove (STB_LOCAL)
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
In kernel/cgroup.c (ffffffff8111a2b5)
Location: kernel/cgroup.c:354
Inline: True
Inline callers:
  - kernel/cgroup.c:css_release_work_fn
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
In kernel/cgroup.c (ffffffff8112216a)
Location: kernel/cgroup.c:357
Inline: True
Inline callers:
  - kernel/cgroup.c:css_release_work_fn
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
In kernel/cgroup/cgroup.c (ffffffff81121cba)
Location: kernel/cgroup/cgroup.c:312
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cgroup_idr_remove(struct idr *idr, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112d3a0)
Location: kernel/cgroup/cgroup.c:317
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
```
**Symbols:**

```
ffffffff8112d3a0-ffffffff8112d3db: cgroup_idr_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cgroup_idr_remove(struct idr *idr, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113c020)
Location: kernel/cgroup/cgroup.c:320
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff8113c020-ffffffff8113c059: cgroup_idr_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgroup_idr_remove(struct idr *idr, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811478b0)
Location: kernel/cgroup/cgroup.c:325
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff811478b0-ffffffff811478e9: cgroup_idr_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_idr_remove(struct idr *idr, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81152b20)
Location: kernel/cgroup/cgroup.c:327
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff81152b20-ffffffff81152b59: cgroup_idr_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_idr_remove(struct idr *idr, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115e770)
Location: kernel/cgroup/cgroup.c:327
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff8115e770-ffffffff8115e7a9: cgroup_idr_remove (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (ffffffff81176930)
Location: kernel/cgroup/cgroup.c:320
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffff8117360a)
Location: kernel/cgroup/cgroup.c:317
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffff811741ea)
Location: kernel/cgroup/cgroup.c:317
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffff8119b27a)
Location: kernel/cgroup/cgroup.c:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffff811cb43a)
Location: kernel/cgroup/cgroup.c:342
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffff8120e89a)
Location: kernel/cgroup/cgroup.c:347
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffff8122429a)
Location: kernel/cgroup/cgroup.c:346
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
In kernel/cgroup/cgroup.c (ffffffff8123bf8a)
Location: kernel/cgroup/cgroup.c:348
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
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
void cgroup_idr_remove(struct idr *idr, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d0d50)
Location: kernel/cgroup/cgroup.c:327
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffff8000101d0d50-ffff8000101d0e14: cgroup_idr_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_idr_remove(struct idr *idr, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0412a14)
Location: kernel/cgroup/cgroup.c:327
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
c0412a14-c0412a58: cgroup_idr_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_idr_remove(struct idr *idr, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000239160)
Location: kernel/cgroup/cgroup.c:327
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
c000000000239160-c0000000002391d4: cgroup_idr_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_idr_remove(struct idr *idr, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe0001497f2)
Location: kernel/cgroup/cgroup.c:327
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffe0001497f2-ffffffe000149844: cgroup_idr_remove (STB_LOCAL)
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
void cgroup_idr_remove(struct idr *idr, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156d90)
Location: kernel/cgroup/cgroup.c:327
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff81156d90-ffffffff81156dc9: cgroup_idr_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_idr_remove(struct idr *idr, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114a0b0)
Location: kernel/cgroup/cgroup.c:327
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff8114a0b0-ffffffff8114a0e9: cgroup_idr_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_idr_remove(struct idr *idr, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81154b60)
Location: kernel/cgroup/cgroup.c:327
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff81154b60-ffffffff81154b99: cgroup_idr_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_idr_remove(struct idr *idr, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81161f40)
Location: kernel/cgroup/cgroup.c:327
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff81161f40-ffffffff81161f79: cgroup_idr_remove (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
