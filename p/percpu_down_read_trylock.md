# Function: <code>percpu_down_read_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int percpu_down_read_trylock(struct percpu_rw_semaphore *brw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810ca260)
Location: kernel/locking/percpu-rwsem.c:85
Inline: False
```
**Symbols:**

```
ffffffff810ca260-ffffffff810ca2c5: percpu_down_read_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int percpu_down_read_trylock(struct percpu_rw_semaphore *brw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810cebf0)
Location: kernel/locking/percpu-rwsem.c:86
Inline: False
```
**Symbols:**

```
ffffffff810cebf0-ffffffff810cec55: percpu_down_read_trylock (STB_GLOBAL)
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
In fs/super.c (ffffffff81248bf1)
Location: include/linux/percpu-rwsem.h:62
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812544fd)
Location: include/linux/percpu-rwsem.h:62
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8127660d)
Location: include/linux/percpu-rwsem.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129c327)
Location: include/linux/percpu-rwsem.h:63
Inline: True
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
In kernel/cpu.c (ffffffff81097cd5)
Location: include/linux/percpu-rwsem.h:63
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In fs/super.c (ffffffff812b1467)
Location: include/linux/percpu-rwsem.h:63
Inline: True
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
In kernel/cpu.c (ffffffff8109bd75)
Location: include/linux/percpu-rwsem.h:61
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In fs/super.c (ffffffff812cdee9)
Location: include/linux/percpu-rwsem.h:61
Inline: True
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
In kernel/cpu.c (ffffffff810a22f5)
Location: include/linux/percpu-rwsem.h:61
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In fs/super.c (ffffffff812df939)
Location: include/linux/percpu-rwsem.h:61
Inline: True
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
In kernel/cpu.c (ffffffff810a9395)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In fs/super.c (ffffffff81316702)
Location: include/linux/percpu-rwsem.h:73
Inline: True
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
In kernel/cpu.c (ffffffff810a4de5)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In kernel/acct.c (ffffffff81165d86)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff8132acac)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff813433d8)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/file.c (ffffffff813fb01b)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff8143eee2)
Location: include/linux/percpu-rwsem.h:73
Inline: True
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
In kernel/cpu.c (ffffffff810a5ae5)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In kernel/acct.c (ffffffff81166ab6)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff8133095f)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff813496c8)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/file.c (ffffffff814014eb)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff81444d22)
Location: include/linux/percpu-rwsem.h:73
Inline: True
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
In kernel/cpu.c (ffffffff810b7475)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In kernel/acct.c (ffffffff8118c276)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff8137e0df)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81397418)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/file.c (ffffffff81453a6b)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff81498bb2)
Location: include/linux/percpu-rwsem.h:73
Inline: True
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
In kernel/cpu.c (ffffffff810cdc65)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In kernel/acct.c (ffffffff811bb687)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff813fdd0f)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814195d7)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/file.c (ffffffff814d0f3c)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff81523a73)
Location: include/linux/percpu-rwsem.h:73
Inline: True
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
In kernel/cpu.c (ffffffff810ebdf5)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In kernel/acct.c (ffffffff811fd4a7)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff8148792f)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814a5017)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/file.c (ffffffff8156997c)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff815c0c5a)
Location: include/linux/percpu-rwsem.h:73
Inline: True
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
In kernel/cpu.c (ffffffff810f7ad5)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In kernel/acct.c (ffffffff81212634)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff814bc790)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814da297)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/file.c (ffffffff815a176c)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff815f83da)
Location: include/linux/percpu-rwsem.h:73
Inline: True
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
In kernel/cpu.c (ffffffff81100ec5)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In kernel/acct.c (ffffffff81229cb4)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff814eecd7)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff8150c886)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/file.c (ffffffff815da51c)
Location: include/linux/percpu-rwsem.h:73
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff81630f8a)
Location: include/linux/percpu-rwsem.h:73
Inline: True
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
In kernel/cpu.c (ffff8000100f7aa0)
Location: include/linux/percpu-rwsem.h:61
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In fs/super.c (ffff800010386348)
Location: include/linux/percpu-rwsem.h:61
Inline: True
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
In kernel/cpu.c (c0355c54)
Location: include/linux/percpu-rwsem.h:61
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In fs/super.c (c056fd8c)
Location: include/linux/percpu-rwsem.h:61
Inline: True
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
In kernel/cpu.c (c00000000013e190)
Location: include/linux/percpu-rwsem.h:61
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In fs/super.c (c00000000047db90)
Location: include/linux/percpu-rwsem.h:61
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000258f36)
Location: include/linux/percpu-rwsem.h:61
Inline: True
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
In kernel/cpu.c (ffffffff8109bc15)
Location: include/linux/percpu-rwsem.h:61
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In fs/super.c (ffffffff812d7f19)
Location: include/linux/percpu-rwsem.h:61
Inline: True
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
In kernel/cpu.c (ffffffff8108a645)
Location: include/linux/percpu-rwsem.h:61
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In fs/super.c (ffffffff812c8b99)
Location: include/linux/percpu-rwsem.h:61
Inline: True
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
In kernel/cpu.c (ffffffff8109bbc5)
Location: include/linux/percpu-rwsem.h:61
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In fs/super.c (ffffffff812d5d29)
Location: include/linux/percpu-rwsem.h:61
Inline: True
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
In kernel/cpu.c (ffffffff810a3c15)
Location: include/linux/percpu-rwsem.h:61
Inline: True
Inline callers:
  - kernel/cpu.c:cpus_read_trylock
```
```
In fs/super.c (ffffffff812e769b)
Location: include/linux/percpu-rwsem.h:61
Inline: True
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
</ul>
