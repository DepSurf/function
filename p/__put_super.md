# Function: <code>__put_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff8120ed80)
Location: fs/super.c:266
Inline: True
Inline callers:
  - fs/super.c:put_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:user_get_super
  - fs/super.c:do_emergency_remount
  - fs/super.c:do_emergency_remount
Direct callers:
  - fs/super.c:put_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:user_get_super
  - fs/super.c:do_emergency_remount
  - fs/super.c:do_emergency_remount
```
**Symbols:**

```
ffffffff8120ed80-ffffffff8120eda5: __put_super.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff81236f79)
Location: fs/super.c:270
Inline: True
Inline callers:
  - fs/super.c:do_emergency_remount
  - fs/super.c:do_emergency_remount
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:put_super
Direct callers:
  - fs/super.c:do_emergency_remount
  - fs/super.c:do_emergency_remount
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
ffffffff812357b0-ffffffff812357d5: __put_super.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff81249c29)
Location: fs/super.c:269
Inline: True
Inline callers:
  - fs/super.c:do_emergency_remount
  - fs/super.c:do_emergency_remount
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:put_super
Direct callers:
  - fs/super.c:do_emergency_remount
  - fs/super.c:do_emergency_remount
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
ffffffff81248360-ffffffff81248385: __put_super.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff81255519)
Location: fs/super.c:268
Inline: True
Inline callers:
  - fs/super.c:do_emergency_remount
  - fs/super.c:do_emergency_remount
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:put_super
Direct callers:
  - fs/super.c:do_emergency_remount
  - fs/super.c:do_emergency_remount
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
ffffffff81253c60-ffffffff81253c85: __put_super.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff812776a9)
Location: fs/super.c:266
Inline: True
Inline callers:
  - fs/super.c:do_emergency_remount
  - fs/super.c:do_emergency_remount
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:put_super
Direct callers:
  - fs/super.c:do_emergency_remount
  - fs/super.c:do_emergency_remount
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
ffffffff81275ce0-ffffffff81275d83: __put_super.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __put_super(struct super_block *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129c240)
Location: fs/super.c:280
Inline: True
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
ffffffff8129c240-ffffffff8129c2e6: __put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __put_super(struct super_block *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b1380)
Location: fs/super.c:284
Inline: True
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
ffffffff812b1380-ffffffff812b1426: __put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff812cfab1)
Location: fs/super.c:285
Inline: True
Inline callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
ffffffff812cde20-ffffffff812cdebb: __put_super.part.0 (STB_LOCAL)
ffffffff812cff77-ffffffff812cffb0: __put_super.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __put_super(struct super_block *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812df850)
Location: fs/super.c:288
Inline: True
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
ffffffff812df850-ffffffff812df901: __put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff813188c1)
Location: fs/super.c:288
Inline: True
Inline callers:
  - fs/super.c:user_get_super
  - fs/super.c:__get_super_thawed
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:drop_super
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:__get_super_thawed
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:drop_super
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff81316610-ffffffff813166be: __put_super.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff81323ddd)
Location: fs/super.c:288
Inline: True
Inline callers:
  - fs/super.c:user_get_super
  - fs/super.c:get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:drop_super
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:drop_super
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff81321ae0-ffffffff81321bc7: __put_super.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff81329e9d)
Location: fs/super.c:288
Inline: True
Inline callers:
  - fs/super.c:user_get_super
  - fs/super.c:get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:drop_super
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:drop_super
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff81327bb0-ffffffff81327c97: __put_super.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff813774cd)
Location: fs/super.c:288
Inline: True
Inline callers:
  - fs/super.c:user_get_super
  - fs/super.c:get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:drop_super
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:drop_super
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff81375180-ffffffff81375267: __put_super.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff813f6725)
Location: fs/super.c:286
Inline: True
Inline callers:
  - fs/super.c:user_get_super
  - fs/super.c:get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:drop_super
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:drop_super
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff813f4490-ffffffff813f4583: __put_super.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff8147f835)
Location: fs/super.c:286
Inline: True
Inline callers:
  - fs/super.c:user_get_super
  - fs/super.c:get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:drop_super
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:drop_super
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff8147d520-ffffffff8147d613: __put_super.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff814b4374)
Location: fs/super.c:285
Inline: True
Inline callers:
  - fs/super.c:fs_mark_dead
  - fs/super.c:user_get_super
  - fs/super.c:get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
Direct callers:
  - fs/super.c:fs_mark_dead
  - fs/super.c:user_get_super
  - fs/super.c:get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff814b22e0-ffffffff814b23cb: __put_super.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __put_super(struct super_block *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff814e46fc)
Location: fs/super.c:403
Inline: True
Inline callers:
  - fs/super.c:bdev_super_lock
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:drop_super
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
Direct callers:
  - fs/super.c:bdev_super_lock
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:drop_super_exclusive
  - fs/super.c:drop_super
  - fs/super.c:grab_super
  - fs/super.c:grab_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff814e39b0-ffffffff814e3a2a: __put_super.part.0 (STB_LOCAL)
ffffffff814e4390-ffffffff814e4418: __put_super (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffff800010388900)
Location: fs/super.c:288
Inline: True
Inline callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
ffff800010386750-ffff800010386840: __put_super.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __put_super(struct super_block *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (c056f1fc)
Location: fs/super.c:288
Inline: True
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
c056f1fc-c056f320: __put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __put_super(struct super_block *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047c870)
Location: fs/super.c:288
Inline: True
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
c00000000047c870-c00000000047c9bc: __put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffe00025aec8)
Location: fs/super.c:288
Inline: True
Inline callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
ffffffe000258d82-ffffffe000258e32: __put_super.part.0 (STB_LOCAL)
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
void __put_super(struct super_block *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7e30)
Location: fs/super.c:288
Inline: True
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
ffffffff812d7e30-ffffffff812d7ee1: __put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __put_super(struct super_block *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c8ab0)
Location: fs/super.c:288
Inline: True
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
ffffffff812c8ab0-ffffffff812c8b61: __put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __put_super(struct super_block *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d5c40)
Location: fs/super.c:288
Inline: True
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
ffffffff812d5c40-ffffffff812d5cf1: __put_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __put_super(struct super_block *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e6c60)
Location: fs/super.c:288
Inline: True
Direct callers:
  - fs/super.c:user_get_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:put_super
```
**Symbols:**

```
ffffffff812e6c60-ffffffff812e6d11: __put_super (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
