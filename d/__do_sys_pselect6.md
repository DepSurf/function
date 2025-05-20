# Function: <code>__do_sys_pselect6</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b4151)
Location: fs/select.c:757
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
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
In fs/select.c (ffffffff812c922c)
Location: fs/select.c:774
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_pselect6(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct __kernel_timespec *tsp, void *sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e5c10)
Location: fs/select.c:769
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff812e5c10-ffffffff812e5d4b: __do_sys_pselect6 (STB_LOCAL)
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
In fs/select.c (ffffffff812f77bf)
Location: fs/select.c:769
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff813303ef)
Location: fs/select.c:791
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8133bd6c)
Location: fs/select.c:791
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
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
In fs/select.c (ffffffff81342229)
Location: fs/select.c:791
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
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
In fs/select.c (ffffffff8138fbe9)
Location: fs/select.c:794
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
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
In fs/select.c (ffffffff81410d99)
Location: fs/select.c:795
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
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
In fs/select.c (ffffffff8149bab9)
Location: fs/select.c:795
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
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
In fs/select.c (ffffffff814d0d48)
Location: fs/select.c:795
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
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
In fs/select.c (ffffffff81503688)
Location: fs/select.c:795
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
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
In fs/select.c (ffff8000103a4b7c)
Location: fs/select.c:769
Inline: True
Inline callers:
  - fs/select.c:__arm64_sys_pselect6
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
In fs/select.c (c05866e0)
Location: fs/select.c:769
Inline: True
Inline callers:
  - fs/select.c:__se_sys_pselect6
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
In fs/select.c (c00000000049e7dc)
Location: fs/select.c:769
Inline: True
Inline callers:
  - fs/select.c:__se_sys_pselect6
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
In fs/select.c (ffffffe00026b886)
Location: fs/select.c:769
Inline: True
Inline callers:
  - fs/select.c:__se_sys_pselect6
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
In fs/select.c (ffffffff812efd9f)
Location: fs/select.c:769
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
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
In fs/select.c (ffffffff812e09cf)
Location: fs/select.c:769
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
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
In fs/select.c (ffffffff812edbaf)
Location: fs/select.c:769
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
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
In fs/select.c (ffffffff812febaf)
Location: fs/select.c:769
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
