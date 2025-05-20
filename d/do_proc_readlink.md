# Function: <code>do_proc_readlink</code>

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
In fs/proc/base.c (ffffffff8127b868)
Location: fs/proc/base.c:1590
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
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
In fs/proc/base.c (ffffffff812a8389)
Location: fs/proc/base.c:1606
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
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
In fs/proc/base.c (ffffffff812bdc69)
Location: fs/proc/base.c:1624
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
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
In fs/proc/base.c (ffffffff812cb2c6)
Location: fs/proc/base.c:1641
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
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
In fs/proc/base.c (ffffffff812ef9fc)
Location: fs/proc/base.c:1642
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
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
In fs/proc/base.c (ffffffff8131c79c)
Location: fs/proc/base.c:1608
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81333fcc)
Location: fs/proc/base.c:1622
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135d64d)
Location: fs/proc/base.c:1635
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81374a5d)
Location: fs/proc/base.c:1635
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_proc_readlink(struct path *path, char *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813bdcc0)
Location: fs/proc/base.c:1746
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
ffffffff813bdcc0-ffffffff813bdd81: do_proc_readlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_proc_readlink(struct path *path, char *buffer, int buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813cfa10)
Location: fs/proc/base.c:1760
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
```
**Symbols:**

```
ffffffff813cfa10-ffffffff813cfad1: do_proc_readlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d680a)
Location: fs/proc/base.c:1759
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8142749a)
Location: fs/proc/base.c:1765
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff814a1077)
Location: fs/proc/base.c:1764
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81536077)
Location: fs/proc/base.c:1765
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156e247)
Location: fs/proc/base.c:1765
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a6bd7)
Location: fs/proc/base.c:1761
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff800010440b14)
Location: fs/proc/base.c:1635
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c060476c)
Location: fs/proc/base.c:1635
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0000000005558e0)
Location: fs/proc/base.c:1635
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
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
In fs/proc/base.c (ffffffe0002d7c06)
Location: fs/proc/base.c:1635
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136d03d)
Location: fs/proc/base.c:1635
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135dacd)
Location: fs/proc/base.c:1635
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136ab0d)
Location: fs/proc/base.c:1635
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8137e51d)
Location: fs/proc/base.c:1635
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
