# Function: <code>cgroup_bpf_put</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cgroup_bpf_put(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81197820)
Location: kernel/bpf/cgroup.c:26
Inline: False
Direct callers:
  - kernel/cgroup.c:css_release_work_fn
```
**Symbols:**

```
ffffffff81197820-ffffffff81197868: cgroup_bpf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cgroup_bpf_put(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8119f3e0)
Location: kernel/bpf/cgroup.c:26
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
```
**Symbols:**

```
ffffffff8119f3e0-ffffffff8119f428: cgroup_bpf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cgroup_bpf_put(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811b26e0)
Location: kernel/bpf/cgroup.c:26
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
```
**Symbols:**

```
ffffffff811b26e0-ffffffff811b27a5: cgroup_bpf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cgroup_bpf_put(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d1d60)
Location: kernel/bpf/cgroup.c:26
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
```
**Symbols:**

```
ffffffff811d1d60-ffffffff811d1e24: cgroup_bpf_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgroup_bpf_put(struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e1ad0)
Location: kernel/bpf/cgroup.c:26
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
```
**Symbols:**

```
ffffffff811e1ad0-ffffffff811e1bbc: cgroup_bpf_put (STB_GLOBAL)
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
In kernel/cgroup/cgroup.c (ffffffff8115b28f)
Location: include/linux/cgroup.h:946
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166f4f)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffffffff81205e19)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117866a)
Location: include/linux/cgroup.h:950
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffffffff8122d599)
Location: include/linux/cgroup.h:950
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117541a)
Location: include/linux/cgroup.h:949
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffffffff81235ac5)
Location: include/linux/cgroup.h:949
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175f8a)
Location: include/linux/cgroup.h:949
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffffffff81239d15)
Location: include/linux/cgroup.h:949
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119d53d)
Location: include/linux/cgroup.h:924
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffffffff81274499)
Location: include/linux/cgroup.h:924
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cd87d)
Location: include/linux/cgroup.h:921
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffffffff812c4b4e)
Location: include/linux/cgroup.h:921
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81210f2d)
Location: include/linux/cgroup.h:848
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffffffff8132a032)
Location: include/linux/cgroup.h:848
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8122691d)
Location: include/linux/cgroup.h:846
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffffffff8135a172)
Location: include/linux/cgroup.h:846
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123e5ad)
Location: include/linux/cgroup.h:844
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffffffff81382d22)
Location: include/linux/cgroup.h:844
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d8e48)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffff80001028f0d8)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041bc88)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (c04be918)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0000000002462f0)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (c00000000033bcf4)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000151dce)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffffffe0001c220a)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115f56f)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffffffff811fe439)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811527ff)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffffffff811f1189)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115d33f)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffffffff811fc209)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116a53f)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
```
```
In kernel/bpf/cgroup.c (ffffffff8120ae3d)
Location: include/linux/cgroup.h:948
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
