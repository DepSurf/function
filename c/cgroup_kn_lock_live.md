# Function: <code>cgroup_kn_lock_live</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81115190)
Location: kernel/cgroup.c:1388
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_release_agent_write
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_rmdir
```
**Symbols:**

```
ffffffff81115190-ffffffff8111525c: cgroup_kn_lock_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111d680)
Location: kernel/cgroup.c:1445
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_rmdir
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff8111d680-ffffffff8111d75f: cgroup_kn_lock_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811259b0)
Location: kernel/cgroup.c:1450
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_rmdir
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff811259b0-ffffffff81125a8f: cgroup_kn_lock_live (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81126da0)
Location: kernel/cgroup/cgroup.c:1342
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81126da0-ffffffff81126e65: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811330c0)
Location: kernel/cgroup/cgroup.c:1513
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff811330c0-ffffffff81133185: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81141760)
Location: kernel/cgroup/cgroup.c:1516
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81141760-ffffffff81141844: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114d210)
Location: kernel/cgroup/cgroup.c:1554
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff8114d210-ffffffff8114d2e7: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81158df0)
Location: kernel/cgroup/cgroup.c:1595
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81158df0-ffffffff81158ea4: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81164a50)
Location: kernel/cgroup/cgroup.c:1595
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81164a50-ffffffff81164b04: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175af0)
Location: kernel/cgroup/cgroup.c:1585
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81175af0-ffffffff81175bac: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172790)
Location: kernel/cgroup/cgroup.c:1582
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81172790-ffffffff8117285e: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173380)
Location: kernel/cgroup/cgroup.c:1583
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81173380-ffffffff8117344e: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119a320)
Location: kernel/cgroup/cgroup.c:1614
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff8119a320-ffffffff8119a3ee: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811ca410)
Location: kernel/cgroup/cgroup.c:1617
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff811ca410-ffffffff811ca4fa: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120d5c0)
Location: kernel/cgroup/cgroup.c:1651
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff8120d5c0-ffffffff8120d6aa: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81222fb0)
Location: kernel/cgroup/cgroup.c:1645
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81222fb0-ffffffff8122309a: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123aca0)
Location: kernel/cgroup/cgroup.c:1640
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff8123aca0-ffffffff8123ad8a: cgroup_kn_lock_live (STB_GLOBAL)
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
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d6370)
Location: kernel/cgroup/cgroup.c:1595
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffff8000101d6370-ffff8000101d64c4: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0419048)
Location: kernel/cgroup/cgroup.c:1595
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
c0419048-c0419158: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000241fd0)
Location: kernel/cgroup/cgroup.c:1595
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
c000000000241fd0-c000000000242144: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014f5d2)
Location: kernel/cgroup/cgroup.c:1595
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffe00014f5d2-ffffffe00014f6ce: cgroup_kn_lock_live (STB_GLOBAL)
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
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115d070)
Location: kernel/cgroup/cgroup.c:1595
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff8115d070-ffffffff8115d124: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81150360)
Location: kernel/cgroup/cgroup.c:1595
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81150360-ffffffff81150414: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115ae40)
Location: kernel/cgroup/cgroup.c:1595
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff8115ae40-ffffffff8115aef4: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cgroup *cgroup_kn_lock_live(struct kernfs_node *kn, bool drain_offline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81167ec0)
Location: kernel/cgroup/cgroup.c:1595
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
**Symbols:**

```
ffffffff81167ec0-ffffffff81167f95: cgroup_kn_lock_live (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool drain_offline</code>
</li>
</ul>
</details>
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
