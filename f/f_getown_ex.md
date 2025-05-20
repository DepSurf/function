# Function: <code>f_getown_ex</code>

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
In fs/fcntl.c (ffffffff8121f161)
Location: fs/fcntl.c:182
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
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
In fs/fcntl.c (ffffffff81246a89)
Location: fs/fcntl.c:186
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
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
In fs/fcntl.c (ffffffff81259a79)
Location: fs/fcntl.c:186
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
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
In fs/fcntl.c (ffffffff81265e2f)
Location: fs/fcntl.c:202
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffffffff8128870f)
Location: fs/fcntl.c:203
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffffffff812aeb4b)
Location: fs/fcntl.c:203
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffffffff812c3c3c)
Location: fs/fcntl.c:203
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffffffff812e0551)
Location: fs/fcntl.c:203
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffffffff812f1ff1)
Location: fs/fcntl.c:203
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int f_getown_ex(struct file *filp, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81329c00)
Location: fs/fcntl.c:203
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81329c00-ffffffff81329cbc: f_getown_ex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int f_getown_ex(struct file *filp, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81335160)
Location: fs/fcntl.c:203
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81335160-ffffffff8133521c: f_getown_ex (STB_LOCAL)
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
In fs/fcntl.c (ffffffff8133b8c1)
Location: fs/fcntl.c:205
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffffffff81389531)
Location: fs/fcntl.c:209
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffffffff8140a5b6)
Location: fs/fcntl.c:205
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffffffff81494e3f)
Location: fs/fcntl.c:206
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffffffff814c9d36)
Location: fs/fcntl.c:207
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffffffff814fc5fb)
Location: fs/fcntl.c:207
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffff80001039beb4)
Location: fs/fcntl.c:203
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (c0581d28)
Location: fs/fcntl.c:203
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (c000000000496da8)
Location: fs/fcntl.c:203
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffffffe000268c7a)
Location: fs/fcntl.c:203
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl
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
In fs/fcntl.c (ffffffff812ea5d1)
Location: fs/fcntl.c:203
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffffffff812db211)
Location: fs/fcntl.c:203
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffffffff812e83e1)
Location: fs/fcntl.c:203
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
In fs/fcntl.c (ffffffff812f938c)
Location: fs/fcntl.c:203
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
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
