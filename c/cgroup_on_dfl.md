# Function: <code>cgroup_on_dfl</code>

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
In kernel/cgroup.c (0)
Location: kernel/cgroup.c:308
Inline: True
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
In kernel/cgroup.c (ffffffff8111ad86)
Location: kernel/cgroup.c:325
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_next
  - kernel/cgroup.c:cgroup_rename
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
In kernel/cgroup.c (ffffffff81122c43)
Location: kernel/cgroup.c:328
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_next
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81127d48)
Location: kernel/cgroup/cgroup.c:283
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81123f40-ffffffff81123f59: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112f8e0)
Location: kernel/cgroup/cgroup.c:288
Inline: True
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8112f8e0-ffffffff8112f8f9: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114376b)
Location: kernel/cgroup/cgroup.c:291
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_control
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8113ddc0-ffffffff8113ddd9: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114f28b)
Location: kernel/cgroup/cgroup.c:296
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_control
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811497b0-ffffffff811497c9: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115af7d)
Location: kernel/cgroup/cgroup.c:298
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_control
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81154df0-ffffffff81154e09: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166c2d)
Location: kernel/cgroup/cgroup.c:298
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_control
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81160a20-ffffffff81160a39: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117833a)
Location: kernel/cgroup/cgroup.c:291
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:link_css_set
  - kernel/cgroup/cgroup.c:compare_css_sets
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81172190-ffffffff811721a9: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117506a)
Location: kernel/cgroup/cgroup.c:288
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:link_css_set
  - kernel/cgroup/cgroup.c:compare_css_sets
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8116ede0-ffffffff8116edf9: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175baa)
Location: kernel/cgroup/cgroup.c:288
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:find_existing_css_set
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8116fa10-ffffffff8116fa29: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119d19a)
Location: kernel/cgroup/cgroup.c:312
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:find_existing_css_set
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81195e80-ffffffff81195e99: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cd4c9)
Location: kernel/cgroup/cgroup.c:313
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:link_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff811c5d50-ffffffff811c5d6f: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81210ab3)
Location: kernel/cgroup/cgroup.c:318
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:link_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff812087a0-ffffffff812087bf: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8122656a)
Location: kernel/cgroup/cgroup.c:317
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:link_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8121df50-ffffffff8121df6f: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123e1fa)
Location: kernel/cgroup/cgroup.c:319
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:link_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81235bb0-ffffffff81235bcf: cgroup_on_dfl (STB_GLOBAL)
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
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d8a64)
Location: kernel/cgroup/cgroup.c:298
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_control
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffff8000101d1b00-ffff8000101d1b38: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041b690)
Location: kernel/cgroup/cgroup.c:298
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:css_visible
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_control
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
c0414ac4-c0414af4: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000245d14)
Location: kernel/cgroup/cgroup.c:298
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:link_css_set
  - kernel/cgroup/cgroup.c:cgroup_control
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
c00000000023c5e0-c00000000023c60c: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000151a18)
Location: kernel/cgroup/cgroup.c:298
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffe00014b5da-ffffffe00014b60c: cgroup_on_dfl (STB_GLOBAL)
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
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115f24d)
Location: kernel/cgroup/cgroup.c:298
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_control
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81159040-ffffffff81159059: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811524dd)
Location: kernel/cgroup/cgroup.c:298
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_control
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff8114c350-ffffffff8114c369: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115d01d)
Location: kernel/cgroup/cgroup.c:298
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_control
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81156e10-ffffffff81156e29: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_on_dfl(const struct cgroup *cgrp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116a15d)
Location: kernel/cgroup/cgroup.c:298
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:css_populate_dir
  - kernel/cgroup/cgroup.c:css_clear_dir
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_control
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
**Symbols:**

```
ffffffff81163dd0-ffffffff81163de9: cgroup_on_dfl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
