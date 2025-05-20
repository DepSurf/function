# Function: <code>css_next_descendant_post</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81116610)
Location: kernel/cgroup.c:3927
Inline: False
Direct callers:
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
```
**Symbols:**

```
ffffffff81116610-ffffffff81116684: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup.c (ffffffff8111ebbe)
Location: kernel/cgroup.c:4116
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
```
**Symbols:**

```
ffffffff8111ac90-ffffffff8111acbf: css_next_descendant_post.part.26 (STB_LOCAL)
ffffffff8111d4a0-ffffffff8111d4fb: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup.c (ffffffff81126f4e)
Location: kernel/cgroup.c:4127
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
```
**Symbols:**

```
ffffffff811227f0-ffffffff8112281f: css_next_descendant_post.part.32 (STB_LOCAL)
ffffffff811257d0-ffffffff8112582b: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81127154)
Location: kernel/cgroup/cgroup.c:3614
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffffffff81122790-ffffffff811227bf: css_next_descendant_post.part.30 (STB_LOCAL)
ffffffff811263c0-ffffffff81126422: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113279a)
Location: kernel/cgroup/cgroup.c:3983
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffffffff8112e2b0-ffffffff8112e2df: css_next_descendant_post.part.32 (STB_LOCAL)
ffffffff811326c0-ffffffff81132722: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81140e55)
Location: kernel/cgroup/cgroup.c:4020
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffffffff8113c8f0-ffffffff8113c91e: css_next_descendant_post.part.35 (STB_LOCAL)
ffffffff81140da0-ffffffff81140e02: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114c895)
Location: kernel/cgroup/cgroup.c:4084
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffffffff81147fb0-ffffffff81147fde: css_next_descendant_post.part.36 (STB_LOCAL)
ffffffff8114c820-ffffffff8114c882: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81158475)
Location: kernel/cgroup/cgroup.c:4341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffffffff81153310-ffffffff81153337: css_next_descendant_post.part.0 (STB_LOCAL)
ffffffff81158400-ffffffff8115846e: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811640f5)
Location: kernel/cgroup/cgroup.c:4343
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffffffff8115ef60-ffffffff8115ef87: css_next_descendant_post.part.0 (STB_LOCAL)
ffffffff81164080-ffffffff811640ee: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174f9d)
Location: kernel/cgroup/cgroup.c:4285
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:blk_throtl_update_limit_valid
  - block/blk-throttle.c:blk_throtl_update_limit_valid
```
**Symbols:**

```
ffffffff81174ef0-ffffffff81174f74: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81171c4d)
Location: kernel/cgroup/cgroup.c:4286
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffffffff81171ba0-ffffffff81171c24: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117286d)
Location: kernel/cgroup/cgroup.c:4299
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffffffff811727d0-ffffffff81172846: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811993ed)
Location: kernel/cgroup/cgroup.c:4474
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffffffff81199350-ffffffff811993c6: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c962d)
Location: kernel/cgroup/cgroup.c:4485
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_can_upgrade
  - block/blk-throttle.c:throtl_can_upgrade
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:blk_throtl_cancel_bios
```
**Symbols:**

```
ffffffff811c94f0-ffffffff811c958c: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120c75d)
Location: kernel/cgroup/cgroup.c:4682
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_next
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_start
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:blk_throtl_cancel_bios
```
**Symbols:**

```
ffffffff8120c600-ffffffff8120c69c: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81221d6d)
Location: kernel/cgroup/cgroup.c:4659
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_next
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_start
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:blk_throtl_cancel_bios
```
**Symbols:**

```
ffffffff81221c10-ffffffff81221ca8: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81239a5d)
Location: kernel/cgroup/cgroup.c:4689
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_restore_control
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/bpf/cgroup_iter.c:bpf_iter_css_next
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_next
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_start
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:blk_throtl_cancel_bios
```
**Symbols:**

```
ffffffff81239900-ffffffff81239998: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d59cc)
Location: kernel/cgroup/cgroup.c:4343
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffff8000101cfb38-ffff8000101cfb74: css_next_descendant_post.part.0 (STB_LOCAL)
ffff8000101d5918-ffff8000101d59ac: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (c0418498)
Location: kernel/cgroup/cgroup.c:4343
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:blk_throtl_update_limit_valid
  - block/blk-throttle.c:blk_throtl_update_limit_valid
```
**Symbols:**

```
c0413518-c0413560: css_next_descendant_post.part.0 (STB_LOCAL)
c0418400-c0418480: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000241284)
Location: kernel/cgroup/cgroup.c:4343
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
c000000000239fe0-c00000000023a028: css_next_descendant_post.part.0 (STB_LOCAL)
c000000000241190-c000000000241260: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014ec8e)
Location: kernel/cgroup/cgroup.c:4343
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffffffe00014a264-ffffffe00014a2a6: css_next_descendant_post.part.0 (STB_LOCAL)
ffffffe00014ebde-ffffffe00014ec6a: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115c715)
Location: kernel/cgroup/cgroup.c:4343
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffffffff81157580-ffffffff811575a7: css_next_descendant_post.part.0 (STB_LOCAL)
ffffffff8115c6a0-ffffffff8115c70e: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114fa05)
Location: kernel/cgroup/cgroup.c:4343
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffffffff8114a8a0-ffffffff8114a8c7: css_next_descendant_post.part.0 (STB_LOCAL)
ffffffff8114f990-ffffffff8114f9fe: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a4e5)
Location: kernel/cgroup/cgroup.c:4343
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffffffff81155350-ffffffff81155377: css_next_descendant_post.part.0 (STB_LOCAL)
ffffffff8115a470-ffffffff8115a4de: css_next_descendant_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct cgroup_subsys_state *css_next_descendant_post(struct cgroup_subsys_state *pos, struct cgroup_subsys_state *root);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81167545)
Location: kernel/cgroup/cgroup.c:4343
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
```
**Symbols:**

```
ffffffff81162870-ffffffff81162897: css_next_descendant_post.part.0 (STB_LOCAL)
ffffffff811674d0-ffffffff8116753e: css_next_descendant_post (STB_GLOBAL)
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
