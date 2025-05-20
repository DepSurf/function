# Function: <code>close_on_exec</code>

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
In fs/exec.c (ffffffff81214048)
Location: include/linux/fdtable.h:33
Inline: True
```
```
In fs/file.c (ffffffff8122aca6)
Location: include/linux/fdtable.h:33
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff812818eb)
Location: include/linux/fdtable.h:33
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffffffff8123adb0)
Location: include/linux/fdtable.h:33
Inline: True
```
```
In fs/file.c (ffffffff81253406)
Location: include/linux/fdtable.h:33
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff812aea2c)
Location: include/linux/fdtable.h:33
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffffffff8124db54)
Location: include/linux/fdtable.h:33
Inline: True
```
```
In fs/file.c (ffffffff81266656)
Location: include/linux/fdtable.h:33
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff812c4403)
Location: include/linux/fdtable.h:33
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffffffff81259b83)
Location: include/linux/fdtable.h:33
Inline: True
```
```
In fs/file.c (ffffffff81273e36)
Location: include/linux/fdtable.h:33
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff812d1697)
Location: include/linux/fdtable.h:33
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffffffff8127bd9d)
Location: include/linux/fdtable.h:35
Inline: True
```
```
In fs/file.c (ffffffff81296706)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff812f5ea6)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffffffff812a2bcd)
Location: include/linux/fdtable.h:35
Inline: True
```
```
In fs/file.c (ffffffff812bcadf)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff813232ee)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffffffff812b7a61)
Location: include/linux/fdtable.h:35
Inline: True
```
```
In fs/file.c (ffffffff812d1d9f)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff8133a5be)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffffffff812d4049)
Location: include/linux/fdtable.h:35
Inline: True
```
```
In fs/file.c (ffffffff812eedcd)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff8136277b)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffffffff812e5bd9)
Location: include/linux/fdtable.h:35
Inline: True
```
```
In fs/file.c (ffffffff8130088d)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff8137a9db)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffffffff8131d62e)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/file.c (ffffffff81339aad)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff813c3a79)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/file.c (ffffffff813457df)
Location: include/linux/fdtable.h:36
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff813d5c07)
Location: include/linux/fdtable.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/file.c (ffffffff8134bb7f)
Location: include/linux/fdtable.h:36
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff813dcc17)
Location: include/linux/fdtable.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/file.c (ffffffff813999bf)
Location: include/linux/fdtable.h:36
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff8142e2f7)
Location: include/linux/fdtable.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/file.c (ffffffff8141c3c8)
Location: include/linux/fdtable.h:36
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff814a7a1d)
Location: include/linux/fdtable.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/file.c (ffffffff814a84d8)
Location: include/linux/fdtable.h:36
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff8153d41d)
Location: include/linux/fdtable.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/file.c (ffffffff814dd4c8)
Location: include/linux/fdtable.h:36
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff815756fd)
Location: include/linux/fdtable.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/file.c (ffffffff8150ffe8)
Location: include/linux/fdtable.h:36
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff815ae05a)
Location: include/linux/fdtable.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffff80001038df50)
Location: include/linux/fdtable.h:35
Inline: True
```
```
In fs/file.c (ffff8000103b27bc)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffff800010446f78)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (c05758b4)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/file.c (c0591a60)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (c060bfa0)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (c00000000048621c)
Location: include/linux/fdtable.h:35
Inline: True
```
```
In fs/file.c (c0000000004ae674)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (c00000000055ce44)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffffffe00025ea7e)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/file.c (ffffffe000276776)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffe0002dcd3c)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffffffff812de1b9)
Location: include/linux/fdtable.h:35
Inline: True
```
```
In fs/file.c (ffffffff812f8e6d)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff81372fbb)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffffffff812cf4e9)
Location: include/linux/fdtable.h:35
Inline: True
```
```
In fs/file.c (ffffffff812e9a8d)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff81363a8b)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffffffff812dbfc9)
Location: include/linux/fdtable.h:35
Inline: True
```
```
In fs/file.c (ffffffff812f6c7d)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff81370a8b)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
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
In fs/exec.c (ffffffff812ecd54)
Location: include/linux/fdtable.h:35
Inline: True
```
```
In fs/file.c (ffffffff81307ed8)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/file.c:get_close_on_exec
```
```
In fs/proc/fd.c (ffffffff8138446b)
Location: include/linux/fdtable.h:35
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
</details>
</li>
</ul>

## Differences
