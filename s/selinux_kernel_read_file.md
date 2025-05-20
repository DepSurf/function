# Function: <code>selinux_kernel_read_file</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81379990)
Location: security/selinux/hooks.c:3794
Inline: False
```
**Symbols:**

```
ffffffff81379990-ffffffff81379a8e: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81390400)
Location: security/selinux/hooks.c:3866
Inline: False
```
**Symbols:**

```
ffffffff81390400-ffffffff813904ef: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a6820)
Location: security/selinux/hooks.c:3824
Inline: False
```
**Symbols:**

```
ffffffff813a6820-ffffffff813a691f: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cc270)
Location: security/selinux/hooks.c:3839
Inline: False
```
**Symbols:**

```
ffffffff813cc270-ffffffff813cc36f: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813ffdc0)
Location: security/selinux/hooks.c:4060
Inline: False
```
**Symbols:**

```
ffffffff813ffdc0-ffffffff813ffec5: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8141be80)
Location: security/selinux/hooks.c:3766
Inline: False
```
**Symbols:**

```
ffffffff8141be80-ffffffff8141be98: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81449820)
Location: security/selinux/hooks.c:3954
Inline: False
```
**Symbols:**

```
ffffffff81449820-ffffffff81449838: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814633c0)
Location: security/selinux/hooks.c:4012
Inline: False
```
**Symbols:**

```
ffffffff814633c0-ffffffff814633d8: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b6ef0)
Location: security/selinux/hooks.c:4005
Inline: False
```
**Symbols:**

```
ffffffff814b6ef0-ffffffff814b6f08: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id, bool contents);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d4bc0)
Location: security/selinux/hooks.c:4019
Inline: True
```
**Symbols:**

```
ffffffff814d4bc0-ffffffff814d4be3: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id, bool contents);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814db9a0)
Location: security/selinux/hooks.c:4178
Inline: True
```
**Symbols:**

```
ffffffff814db9a0-ffffffff814db9c0: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id, bool contents);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81534e20)
Location: security/selinux/hooks.c:4163
Inline: True
```
**Symbols:**

```
ffffffff81534e20-ffffffff81534e40: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id, bool contents);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815cb0b0)
Location: security/selinux/hooks.c:4059
Inline: True
```
**Symbols:**

```
ffffffff815cb0b0-ffffffff815cb0e4: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id, bool contents);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816781a0)
Location: security/selinux/hooks.c:4077
Inline: True
```
**Symbols:**

```
ffffffff816781a0-ffffffff816781d4: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id, bool contents);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816b0430)
Location: security/selinux/hooks.c:4050
Inline: True
```
**Symbols:**

```
ffffffff816b0430-ffffffff816b0464: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id, bool contents);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816ed3c0)
Location: security/selinux/hooks.c:4137
Inline: True
```
**Symbols:**

```
ffffffff816ed3c0-ffffffff816ed3f4: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010551250)
Location: security/selinux/hooks.c:4012
Inline: False
```
**Symbols:**

```
ffff800010551250-ffff800010551298: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0703de8)
Location: security/selinux/hooks.c:4012
Inline: False
```
**Symbols:**

```
c0703de8-c0703e14: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a8050)
Location: security/selinux/hooks.c:4012
Inline: False
```
**Symbols:**

```
c0000000006a8050-c0000000006a8074: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003aa5e4)
Location: security/selinux/hooks.c:4012
Inline: False
```
**Symbols:**

```
ffffffe0003aa5e4-ffffffe0003aa628: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145b9a0)
Location: security/selinux/hooks.c:4012
Inline: False
```
**Symbols:**

```
ffffffff8145b9a0-ffffffff8145b9b8: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144c3d0)
Location: security/selinux/hooks.c:4012
Inline: False
```
**Symbols:**

```
ffffffff8144c3d0-ffffffff8144c3e8: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81457a40)
Location: security/selinux/hooks.c:4012
Inline: False
```
**Symbols:**

```
ffffffff81457a40-ffffffff81457a58: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int selinux_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146c9a0)
Location: security/selinux/hooks.c:4012
Inline: False
```
**Symbols:**

```
ffffffff8146c9a0-ffffffff8146c9b8: selinux_kernel_read_file (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool contents</code>
</li>
</ul>
</details>
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
