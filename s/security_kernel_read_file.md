# Function: <code>security_kernel_read_file</code>

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
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81371c90)
Location: security/security.c:924
Inline: False
Direct callers:
  - kernel/module.c:SYSC_init_module
```
**Symbols:**

```
ffffffff81371c90-ffffffff81371ce8: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813885c0)
Location: security/security.c:945
Inline: False
Direct callers:
  - kernel/module.c:SYSC_init_module
```
**Symbols:**

```
ffffffff813885c0-ffffffff81388618: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139d620)
Location: security/security.c:1582
Inline: False
Direct callers:
  - kernel/module.c:SYSC_init_module
```
**Symbols:**

```
ffffffff8139d620-ffffffff8139d678: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c2ef0)
Location: security/security.c:1544
Inline: False
Direct callers:
  - kernel/module.c:SYSC_init_module
```
**Symbols:**

```
ffffffff813c2ef0-ffffffff813c2f4e: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f3ae0)
Location: security/security.c:1048
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
```
**Symbols:**

```
ffffffff813f3ae0-ffffffff813f3b2d: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140eef0)
Location: security/security.c:1645
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
```
**Symbols:**

```
ffffffff8140eef0-ffffffff8140ef3d: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143c2a0)
Location: security/security.c:1664
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
```
**Symbols:**

```
ffffffff8143c2a0-ffffffff8143c2f6: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455e50)
Location: security/security.c:1703
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
```
**Symbols:**

```
ffffffff81455e50-ffffffff81455e9d: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8c80)
Location: security/security.c:1887
Inline: False
```
**Symbols:**

```
ffffffff814a8c80-ffffffff814a8ccd: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c61f0)
Location: security/security.c:1889
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file
  - fs/kernel_read_file.c:kernel_read_file
```
**Symbols:**

```
ffffffff814c61f0-ffffffff814c624b: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc4a0)
Location: security/security.c:1939
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file
  - fs/kernel_read_file.c:kernel_read_file
```
**Symbols:**

```
ffffffff814cc4a0-ffffffff814cc4fb: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525330)
Location: security/security.c:1947
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file
  - fs/kernel_read_file.c:kernel_read_file
```
**Symbols:**

```
ffffffff81525330-ffffffff8152538b: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b92c0)
Location: security/security.c:1952
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file
  - fs/kernel_read_file.c:kernel_read_file
```
**Symbols:**

```
ffffffff815b92c0-ffffffff815b9337: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81664a50)
Location: security/security.c:1999
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file
  - fs/kernel_read_file.c:kernel_read_file
```
**Symbols:**

```
ffffffff81664a50-ffffffff81664ac7: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169cf30)
Location: security/security.c:3197
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file
  - fs/kernel_read_file.c:kernel_read_file
```
**Symbols:**

```
ffffffff8169cf30-ffffffff8169cfa7: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d9a10)
Location: security/security.c:3269
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file
  - fs/kernel_read_file.c:kernel_read_file
```
**Symbols:**

```
ffffffff816d9a10-ffffffff816d9a87: security_kernel_read_file (STB_GLOBAL)
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
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010541558)
Location: security/security.c:1703
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
```
**Symbols:**

```
ffff800010541558-ffff8000105415c0: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f754c)
Location: security/security.c:1703
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
```
**Symbols:**

```
c06f754c-c06f75b0: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000693d20)
Location: security/security.c:1703
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
```
**Symbols:**

```
c000000000693d20-c000000000693db4: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e26c)
Location: security/security.c:1703
Inline: False
```
**Symbols:**

```
ffffffe00039e26c-ffffffe00039e2ba: security_kernel_read_file (STB_GLOBAL)
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
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e430)
Location: security/security.c:1703
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
```
**Symbols:**

```
ffffffff8144e430-ffffffff8144e47d: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ee80)
Location: security/security.c:1703
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
```
**Symbols:**

```
ffffffff8143ee80-ffffffff8143eecd: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a4d0)
Location: security/security.c:1703
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
```
**Symbols:**

```
ffffffff8144a4d0-ffffffff8144a51d: security_kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_kernel_read_file(struct file *file, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814618a0)
Location: security/security.c:1703
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
```
**Symbols:**

```
ffffffff814618a0-ffffffff814618ed: security_kernel_read_file (STB_GLOBAL)
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
