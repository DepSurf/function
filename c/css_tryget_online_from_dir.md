# Function: <code>css_tryget_online_from_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811198e0)
Location: kernel/cgroup.c:5912
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff811198e0-ffffffff811199d1: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81121560)
Location: kernel/cgroup.c:6151
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff81121560-ffffffff8112164c: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81129ae0)
Location: kernel/cgroup.c:6180
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff81129ae0-ffffffff81129bd0: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811288a0)
Location: kernel/cgroup/cgroup.c:5000
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff811288a0-ffffffff81128991: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81134ef0)
Location: kernel/cgroup/cgroup.c:5667
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff81134ef0-ffffffff81134fe1: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81143630)
Location: kernel/cgroup/cgroup.c:5705
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff81143630-ffffffff81143724: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114f160)
Location: kernel/cgroup/cgroup.c:5808
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff8114f160-ffffffff8114f244: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115ae50)
Location: kernel/cgroup/cgroup.c:6185
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff8115ae50-ffffffff8115af36: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166b00)
Location: kernel/cgroup/cgroup.c:6200
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff81166b00-ffffffff81166be6: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81177cb0)
Location: kernel/cgroup/cgroup.c:6270
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff81177cb0-ffffffff81177d93: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811749b0)
Location: kernel/cgroup/cgroup.c:6262
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff811749b0-ffffffff81174ab5: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175570)
Location: kernel/cgroup/cgroup.c:6240
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff81175570-ffffffff81175675: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119cae0)
Location: kernel/cgroup/cgroup.c:6486
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff8119cae0-ffffffff8119cc03: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811ccdc0)
Location: kernel/cgroup/cgroup.c:6516
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff811ccdc0-ffffffff811ccefe: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81210370)
Location: kernel/cgroup/cgroup.c:6762
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff81210370-ffffffff812104ad: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81225d80)
Location: kernel/cgroup/cgroup.c:6745
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_v1v2_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff81225d80-ffffffff81225ebd: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123da10)
Location: kernel/cgroup/cgroup.c:6786
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_v1v2_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff8123da10-ffffffff8123db4d: css_tryget_online_from_dir (STB_GLOBAL)
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
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d8948)
Location: kernel/cgroup/cgroup.c:6200
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffff8000101d8948-ffff8000101d8a18: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041b52c)
Location: kernel/cgroup/cgroup.c:6200
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
c041b52c-c041b64c: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000245b10)
Location: kernel/cgroup/cgroup.c:6200
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
c000000000245b10-c000000000245ca8: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe0001518de)
Location: kernel/cgroup/cgroup.c:6200
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffe0001518de-ffffffe0001519d2: css_tryget_online_from_dir (STB_GLOBAL)
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
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115f120)
Location: kernel/cgroup/cgroup.c:6200
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff8115f120-ffffffff8115f206: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811523b0)
Location: kernel/cgroup/cgroup.c:6200
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff811523b0-ffffffff81152496: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115cef0)
Location: kernel/cgroup/cgroup.c:6200
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff8115cef0-ffffffff8115cfd6: css_tryget_online_from_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_tryget_online_from_dir(struct dentry *dentry, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116a010)
Location: kernel/cgroup/cgroup.c:6200
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:memcg_write_event_control
```
**Symbols:**

```
ffffffff8116a010-ffffffff8116a11c: css_tryget_online_from_dir (STB_GLOBAL)
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
