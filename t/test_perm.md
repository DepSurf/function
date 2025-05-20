# Function: <code>test_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int test_perm(int mode, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812841d0)
Location: fs/proc/proc_sysctl.c:406
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff812841d0-ffffffff8128422b: test_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int test_perm(int mode, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b1280)
Location: fs/proc/proc_sysctl.c:406
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff812b1280-ffffffff812b12db: test_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int test_perm(int mode, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c6b10)
Location: fs/proc/proc_sysctl.c:406
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff812c6b10-ffffffff812c6b6b: test_perm (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff812d3e50)
Location: fs/proc/proc_sysctl.c:433
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff812f8683)
Location: fs/proc/proc_sysctl.c:434
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff81325783)
Location: fs/proc/proc_sysctl.c:434
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff8133c923)
Location: fs/proc/proc_sysctl.c:434
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff81364bb3)
Location: fs/proc/proc_sysctl.c:439
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff8137ce43)
Location: fs/proc/proc_sysctl.c:439
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff813c6873)
Location: fs/proc/proc_sysctl.c:407
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff813d8813)
Location: fs/proc/proc_sysctl.c:408
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff813df6e3)
Location: fs/proc/proc_sysctl.c:403
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff81431093)
Location: fs/proc/proc_sysctl.c:403
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff814ab0a3)
Location: fs/proc/proc_sysctl.c:428
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff81540f33)
Location: fs/proc/proc_sysctl.c:421
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff815792d3)
Location: fs/proc/proc_sysctl.c:415
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff815b1b03)
Location: fs/proc/proc_sysctl.c:417
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffff800010449830)
Location: fs/proc/proc_sysctl.c:439
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (c060ee60)
Location: fs/proc/proc_sysctl.c:439
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (c00000000056086c)
Location: fs/proc/proc_sysctl.c:439
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffe0002df148)
Location: fs/proc/proc_sysctl.c:439
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff81375423)
Location: fs/proc/proc_sysctl.c:439
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff81365ef3)
Location: fs/proc/proc_sysctl.c:439
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff81372ef3)
Location: fs/proc/proc_sysctl.c:439
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
In fs/proc/proc_sysctl.c (ffffffff81386a43)
Location: fs/proc/proc_sysctl.c:439
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:sysctl_perm
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
</ul>
