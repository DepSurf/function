# Function: <code>blkcg_css_online</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkcg_css_online(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8156a310)
Location: block/blk-cgroup.c:1009
Inline: False
```
**Symbols:**

```
ffffffff8156a310-ffffffff8156a365: blkcg_css_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkcg_css_online(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81584d60)
Location: block/blk-cgroup.c:1133
Inline: False
```
**Symbols:**

```
ffffffff81584d60-ffffffff81584db5: blkcg_css_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkcg_css_online(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158ba20)
Location: block/blk-cgroup.c:1138
Inline: False
```
**Symbols:**

```
ffffffff8158ba20-ffffffff8158ba75: blkcg_css_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkcg_css_online(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f0db0)
Location: block/blk-cgroup.c:1146
Inline: False
```
**Symbols:**

```
ffffffff815f0db0-ffffffff815f0e05: blkcg_css_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int blkcg_css_online(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a2280)
Location: block/blk-cgroup.c:1241
Inline: True
```
**Symbols:**

```
ffffffff816a2280-ffffffff816a22ef: blkcg_css_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkcg_css_online(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81760c40)
Location: block/blk-cgroup.c:1254
Inline: False
```
**Symbols:**

```
ffffffff81760c40-ffffffff81760ca7: blkcg_css_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blkcg_css_online(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8179fad0)
Location: block/blk-cgroup.c:1385
Inline: False
```
**Symbols:**

```
ffffffff8179fad0-ffffffff8179fb37: blkcg_css_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blkcg_css_online(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e35a0)
Location: block/blk-cgroup.c:1398
Inline: False
```
**Symbols:**

```
ffffffff817e35a0-ffffffff817e3607: blkcg_css_online (STB_LOCAL)
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
