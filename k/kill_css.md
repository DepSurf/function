# Function: <code>kill_css</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811145d0)
Location: kernel/cgroup.c:5189
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_subtree_control_write
```
**Symbols:**

```
ffffffff811145d0-ffffffff81114628: kill_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111bf80)
Location: kernel/cgroup.c:5391
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff8111bf80-ffffffff8111bfd6: kill_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811242c0)
Location: kernel/cgroup.c:5410
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff811242c0-ffffffff81124316: kill_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81123870)
Location: kernel/cgroup/cgroup.c:4362
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff81123870-ffffffff811238cd: kill_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112f710)
Location: kernel/cgroup/cgroup.c:5000
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff8112f710-ffffffff8112f76d: kill_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113dc00)
Location: kernel/cgroup/cgroup.c:5040
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff8113dc00-ffffffff8113dc5c: kill_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811495f0)
Location: kernel/cgroup/cgroup.c:5134
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff811495f0-ffffffff8114964c: kill_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81154a10)
Location: kernel/cgroup/cgroup.c:5463
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff81154a10-ffffffff81154a6c: kill_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81160640)
Location: kernel/cgroup/cgroup.c:5478
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff81160640-ffffffff8116069c: kill_css (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (ffffffff81176be2)
Location: kernel/cgroup/cgroup.c:5420
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
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
In kernel/cgroup/cgroup.c (ffffffff811738e9)
Location: kernel/cgroup/cgroup.c:5412
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
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
In kernel/cgroup/cgroup.c (ffffffff811744b9)
Location: kernel/cgroup/cgroup.c:5393
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
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
In kernel/cgroup/cgroup.c (ffffffff8119b553)
Location: kernel/cgroup/cgroup.c:5583
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
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
In kernel/cgroup/cgroup.c (ffffffff811cb75a)
Location: kernel/cgroup/cgroup.c:5594
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
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
In kernel/cgroup/cgroup.c (ffffffff8120ebd9)
Location: kernel/cgroup/cgroup.c:5810
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
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
In kernel/cgroup/cgroup.c (ffffffff812245e9)
Location: kernel/cgroup/cgroup.c:5791
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
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
In kernel/cgroup/cgroup.c (ffffffff8123c2d9)
Location: kernel/cgroup/cgroup.c:5824
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
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
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d11f0)
Location: kernel/cgroup/cgroup.c:5478
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffff8000101d11f0-ffff8000101d1260: kill_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c04145fc)
Location: kernel/cgroup/cgroup.c:5478
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
c04145fc-c0414694: kill_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023bbb0)
Location: kernel/cgroup/cgroup.c:5478
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
c00000000023bbb0-c00000000023bca8: kill_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014b076)
Location: kernel/cgroup/cgroup.c:5478
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffe00014b076-ffffffe00014b10a: kill_css (STB_LOCAL)
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
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81158c60)
Location: kernel/cgroup/cgroup.c:5478
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff81158c60-ffffffff81158cbc: kill_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114be50)
Location: kernel/cgroup/cgroup.c:5478
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff8114be50-ffffffff8114beac: kill_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156a30)
Location: kernel/cgroup/cgroup.c:5478
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff81156a30-ffffffff81156a8c: kill_css (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kill_css(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811639d0)
Location: kernel/cgroup/cgroup.c:5478
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
```
**Symbols:**

```
ffffffff811639d0-ffffffff81163a34: kill_css (STB_LOCAL)
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
