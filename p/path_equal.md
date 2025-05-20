# Function: <code>path_equal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81092b2d)
Location: include/linux/path.h:15
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff8121679f)
Location: include/linux/path.h:15
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffff81230532)
Location: include/linux/path.h:15
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81095cb0)
Location: include/linux/path.h:15
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff8123d6ac)
Location: include/linux/path.h:15
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffff81258bc2)
Location: include/linux/path.h:15
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109aca0)
Location: include/linux/path.h:15
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff8125044c)
Location: include/linux/path.h:15
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffff8126c072)
Location: include/linux/path.h:15
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81097a9e)
Location: include/linux/path.h:15
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff8125c690)
Location: include/linux/path.h:15
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffff81279860)
Location: include/linux/path.h:15
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109e78e)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff812838dd)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff8129c290)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a3fea)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff812aa8ce)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff812c27c2)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810acdba)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff812bfaf8)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffff812d7a62)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b25f6)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff812dcd37)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffff812f5f3f)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/sys.c (ffffffff810b8cc6)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff812ee86f)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffff81307abf)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/sys.c (ffffffff810c0706)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff81322644)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffff81340f9f)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/sys.c (ffffffff810bcd8a)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff8132dbe4)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffff8134d08f)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/sys.c (ffffffff810be61f)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff8133415d)
Location: include/linux/path.h:16
Inline: True
```
```
In fs/namespace.c (ffffffff81353c6f)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/fork.c (ffffffff810b32d3)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In fs/namei.c (ffffffff81381aad)
Location: include/linux/path.h:16
Inline: True
```
```
In fs/namespace.c (ffffffff813a20bf)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/fork.c (ffffffff810c94f3)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In fs/namei.c (ffffffff814056c6)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
```
```
In fs/namespace.c (ffffffff81425b97)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/fork.c (ffffffff810e6a4f)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In fs/namei.c (ffffffff8148fba1)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffff814b2397)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/fork.c (ffffffff810f23fa)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In fs/namei.c (ffffffff814c4e26)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
```
```
In fs/namespace.c (ffffffff814e73e7)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/fork.c (ffffffff810fbfc8)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In fs/namei.c (ffffffff814f7606)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
```
```
In fs/namespace.c (ffffffff8151b277)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/sys.c (ffff8000101150b4)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffff8000103942ec)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffff8000103baf7c)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/sys.c (c036aefc)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (c057e5e0)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (c0598d28)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/sys.c (c00000000015d03c)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (c00000000049203c)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (c0000000004b88fc)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/sys.c (ffffffe0000d20fe)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffe000265e90)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffe00027d090)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/sys.c (ffffffff810b3036)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff812e6e4f)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffff8130009f)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/sys.c (ffffffff810a1966)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff812d7a8f)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffff812f0cbf)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/sys.c (ffffffff810b2596)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff812e4c5f)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffff812fde8f)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
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
In kernel/sys.c (ffffffff810bab96)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In fs/namei.c (ffffffff812f5bdf)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:follow_dotdot_rcu
```
```
In fs/namespace.c (ffffffff8130f1d3)
Location: include/linux/path.h:16
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
```
</details>
</li>
</ul>

## Differences
