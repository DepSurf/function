# Function: <code>blkcg_pin_online</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8127823c)
Location: include/linux/blk-cgroup.h:423
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In block/blk-cgroup.c (ffffffff8156a321)
Location: include/linux/blk-cgroup.h:423
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_online
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
In mm/backing-dev.c (ffffffff812829cd)
Location: include/linux/blk-cgroup.h:413
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In block/blk-cgroup.c (ffffffff81584d71)
Location: include/linux/blk-cgroup.h:413
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_online
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
In mm/backing-dev.c (ffffffff81287af2)
Location: include/linux/blk-cgroup.h:413
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In block/blk-cgroup.c (ffffffff8158ba31)
Location: include/linux/blk-cgroup.h:413
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_online
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
In mm/backing-dev.c (ffffffff812c7294)
Location: include/linux/blk-cgroup.h:418
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In block/blk-cgroup.c (ffffffff815f0dc1)
Location: include/linux/blk-cgroup.h:418
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blkcg_pin_online(struct cgroup_subsys_state *blkcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a228f)
Location: block/blk-cgroup.c:1112
Inline: True
Direct callers:
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff816a4580-ffffffff816a45f2: blkcg_pin_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blkcg_pin_online(struct cgroup_subsys_state *blkcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81760c51)
Location: block/blk-cgroup.c:1124
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_online
Direct callers:
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff817632a0-ffffffff81763312: blkcg_pin_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blkcg_pin_online(struct cgroup_subsys_state *blkcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8179fae1)
Location: block/blk-cgroup.c:1257
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_online
Direct callers:
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff817a23f0-ffffffff817a2462: blkcg_pin_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blkcg_pin_online(struct cgroup_subsys_state *blkcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e35b1)
Location: block/blk-cgroup.c:1270
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_online
Direct callers:
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff817e5f30-ffffffff817e5fa2: blkcg_pin_online (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
