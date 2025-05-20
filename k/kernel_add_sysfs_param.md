# Function: <code>kernel_add_sysfs_param</code>

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
In kernel/params.c (ffffffff81f7cae0)
Location: kernel/params.c:833
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
In kernel/params.c (ffffffff81fa589f)
Location: kernel/params.c:833
Inline: True
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
In kernel/params.c (ffffffff81fe13a4)
Location: kernel/params.c:833
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
In kernel/params.c (ffffffff820c220f)
Location: kernel/params.c:781
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
In kernel/params.c (ffffffff826ca32a)
Location: kernel/params.c:794
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
In kernel/params.c (ffffffff826f4576)
Location: kernel/params.c:794
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
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
In kernel/params.c (ffffffff828ab363)
Location: kernel/params.c:794
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
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
In kernel/params.c (ffffffff828c3b42)
Location: kernel/params.c:782
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
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
In kernel/params.c (ffffffff828cc119)
Location: kernel/params.c:777
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kernel_add_sysfs_param(const char *name, const struct kernel_param *kparam, unsigned int name_skip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff82cedf66)
Location: kernel/params.c:777
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_builtin
```
**Symbols:**

```
ffffffff82cedf66-ffffffff82cedfe2: kernel_add_sysfs_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kernel_add_sysfs_param(const char *name, const struct kernel_param *kparam, unsigned int name_skip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff82fda5c0)
Location: kernel/params.c:778
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_builtin
```
**Symbols:**

```
ffffffff82fda5c0-ffffffff82fda63c: kernel_add_sysfs_param (STB_LOCAL)
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
In kernel/params.c (ffffffff831e4ff6)
Location: kernel/params.c:778
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_builtin
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
In kernel/params.c (ffffffff832c8e76)
Location: kernel/params.c:796
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_builtin
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
In kernel/params.c (ffffffff8347c00a)
Location: kernel/params.c:796
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_builtin
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
In kernel/params.c (ffffffff83ea723d)
Location: kernel/params.c:796
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_builtin
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
In kernel/params.c (ffffffff836cbbc6)
Location: kernel/params.c:797
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_builtin
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
In kernel/params.c (ffffffff838fcfb6)
Location: kernel/params.c:801
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_builtin
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
In kernel/params.c (ffff8000114439a4)
Location: kernel/params.c:777
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
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
In kernel/params.c (c151d8a0)
Location: kernel/params.c:777
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
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
In kernel/params.c (c000000001367b74)
Location: kernel/params.c:777
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
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
In kernel/params.c (ffffffe000005aae)
Location: kernel/params.c:777
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
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
In kernel/params.c (ffffffff828b4f0c)
Location: kernel/params.c:777
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
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
In kernel/params.c (ffffffff828ad08d)
Location: kernel/params.c:777
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
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
In kernel/params.c (ffffffff828c7e0b)
Location: kernel/params.c:777
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
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
In kernel/params.c (ffffffff828cd162)
Location: kernel/params.c:777
Inline: True
Inline callers:
  - kernel/params.c:param_sysfs_init
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
