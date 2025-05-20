# Function: <code>cpuset_css_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8111b410)
Location: kernel/cpuset.c:1935
Inline: False
```
**Symbols:**

```
ffffffff8111b410-ffffffff8111b501: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff81123320)
Location: kernel/cpuset.c:1940
Inline: False
```
**Symbols:**

```
ffffffff81123320-ffffffff81123411: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8112b960)
Location: kernel/cpuset.c:1940
Inline: False
```
**Symbols:**

```
ffffffff8112b960-ffffffff8112baad: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8112d150)
Location: kernel/cgroup/cpuset.c:1929
Inline: True
```
**Symbols:**

```
ffffffff8112d150-ffffffff8112d280: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8113a030)
Location: kernel/cgroup/cpuset.c:1939
Inline: True
```
**Symbols:**

```
ffffffff8113a030-ffffffff8113a160: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81148820)
Location: kernel/cgroup/cpuset.c:1940
Inline: True
```
**Symbols:**

```
ffffffff81148820-ffffffff81148962: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811543b0)
Location: kernel/cgroup/cpuset.c:2656
Inline: True
```
**Symbols:**

```
ffffffff811543b0-ffffffff811544d8: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811608e0)
Location: kernel/cgroup/cpuset.c:2617
Inline: True
```
**Symbols:**

```
ffffffff811608e0-ffffffff81160a19: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116c5b0)
Location: kernel/cgroup/cpuset.c:2699
Inline: True
```
**Symbols:**

```
ffffffff8116c5b0-ffffffff8116c6e9: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117dd40)
Location: kernel/cgroup/cpuset.c:2701
Inline: True
```
**Symbols:**

```
ffffffff8117dd40-ffffffff8117de68: cpuset_css_alloc.part.0 (STB_LOCAL)
ffffffff8117de70-ffffffff8117de8d: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117ab90)
Location: kernel/cgroup/cpuset.c:2724
Inline: True
```
**Symbols:**

```
ffffffff8117ab90-ffffffff8117acb8: cpuset_css_alloc.part.0 (STB_LOCAL)
ffffffff8117acc0-ffffffff8117acdd: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117b9f0)
Location: kernel/cgroup/cpuset.c:2724
Inline: True
```
**Symbols:**

```
ffffffff8117b9f0-ffffffff8117bb27: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811a34a0)
Location: kernel/cgroup/cpuset.c:2777
Inline: True
```
**Symbols:**

```
ffffffff811a34a0-ffffffff811a35e1: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811d45f0)
Location: kernel/cgroup/cpuset.c:2817
Inline: True
```
**Symbols:**

```
ffffffff811d45f0-ffffffff811d4741: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81218650)
Location: kernel/cgroup/cpuset.c:3090
Inline: True
```
**Symbols:**

```
ffffffff81218650-ffffffff812187b0: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8122dec0)
Location: kernel/cgroup/cpuset.c:3187
Inline: True
```
**Symbols:**

```
ffffffff8122dec0-ffffffff8122e020: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81247c90)
Location: kernel/cgroup/cpuset.c:4005
Inline: True
```
**Symbols:**

```
ffffffff81247c90-ffffffff81247e6c: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e0e18)
Location: kernel/cgroup/cpuset.c:2699
Inline: True
```
**Symbols:**

```
ffff8000101e0e18-ffff8000101e0ed8: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c04222dc)
Location: kernel/cgroup/cpuset.c:2699
Inline: True
```
**Symbols:**

```
c04222dc-c0422378: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c00000000024fb10)
Location: kernel/cgroup/cpuset.c:2699
Inline: True
```
**Symbols:**

```
c00000000024fb10-c00000000024fc20: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe000157592)
Location: kernel/cgroup/cpuset.c:2699
Inline: True
```
**Symbols:**

```
ffffffe000157592-ffffffe000157610: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81164bd0)
Location: kernel/cgroup/cpuset.c:2699
Inline: True
```
**Symbols:**

```
ffffffff81164bd0-ffffffff81164d09: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81157e10)
Location: kernel/cgroup/cpuset.c:2699
Inline: True
```
**Symbols:**

```
ffffffff81157e10-ffffffff81157f49: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811629a0)
Location: kernel/cgroup/cpuset.c:2699
Inline: True
```
**Symbols:**

```
ffffffff811629a0-ffffffff81162ad9: cpuset_css_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *cpuset_css_alloc(struct cgroup_subsys_state *parent_css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116ff10)
Location: kernel/cgroup/cpuset.c:2699
Inline: True
```
**Symbols:**

```
ffffffff8116ff10-ffffffff81170049: cpuset_css_alloc (STB_LOCAL)
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
