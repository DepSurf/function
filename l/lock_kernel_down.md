# Function: <code>lock_kernel_down</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void lock_kernel_down();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lock_down.c (ffffffff813fcb80)
Location: security/lock_down.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff813fcb80-ffffffff813fcb92: lock_kernel_down (STB_GLOBAL)
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
In security/lock_down.c (ffffffff826ee39a)
Location: security/lock_down.c:27
Inline: True
Inline callers:
  - security/lock_down.c:lockdown_param
  - security/lock_down.c:init_lockdown
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
In security/lock_down.c (ffffffff8271892c)
Location: security/lock_down.c:31
Inline: True
Inline callers:
  - security/lock_down.c:lockdown_param
  - security/lock_down.c:init_lockdown
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
In security/lock_down.c (ffffffff828d0991)
Location: security/lock_down.c:31
Inline: True
Inline callers:
  - security/lock_down.c:lockdown_param
  - security/lock_down.c:init_lockdown
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
In security/lock_down.c (ffffffff828ea72d)
Location: security/lock_down.c:31
Inline: True
Inline callers:
  - security/lock_down.c:lockdown_param
  - security/lock_down.c:init_lockdown
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff814b3807)
Location: security/lockdown/lockdown.c:53
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffffffff814b3780-ffffffff814b379c: lock_kernel_down (STB_LOCAL)
ffffffff814b39d9-ffffffff814b39f5: lock_kernel_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff81512d37)
Location: security/lockdown/lockdown.c:26
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
Direct callers:
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffffffff81512ca0-ffffffff81512cbc: lock_kernel_down (STB_LOCAL)
ffffffff81512f09-ffffffff81512f25: lock_kernel_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff8152ff07)
Location: security/lockdown/lockdown.c:26
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
Direct callers:
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffffffff8152fe70-ffffffff8152fe8c: lock_kernel_down (STB_LOCAL)
ffffffff81bf1951-ffffffff81bf196d: lock_kernel_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff81536107)
Location: security/lockdown/lockdown.c:26
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
Direct callers:
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffffffff81536070-ffffffff81536087: lock_kernel_down (STB_LOCAL)
ffffffff81be396e-ffffffff81be398b: lock_kernel_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff8159472c)
Location: security/lockdown/lockdown.c:26
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
Direct callers:
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffffffff81594690-ffffffff815946a7: lock_kernel_down (STB_LOCAL)
ffffffff81cd6aa5-ffffffff81cd6ac2: lock_kernel_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff81636804)
Location: security/lockdown/lockdown.c:26
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
Direct callers:
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffffffff81636760-ffffffff8163677f: lock_kernel_down (STB_LOCAL)
ffffffff81e899e1-ffffffff81e89a06: lock_kernel_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff816ed934)
Location: security/lockdown/lockdown.c:27
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffffffff816ed860-ffffffff816ed8a0: lock_kernel_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff81727d44)
Location: security/lockdown/lockdown.c:27
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffffffff81727c70-ffffffff81727cb0: lock_kernel_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff81769074)
Location: security/lockdown/lockdown.c:27
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffffffff81768fa0-ffffffff81768fe0: lock_kernel_down (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffff8000105ab518)
Location: security/lockdown/lockdown.c:53
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffff8000105ab440-ffff8000105ab498: lock_kernel_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (c075b0e4)
Location: security/lockdown/lockdown.c:53
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
c075b008-c075b058: lock_kernel_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (c0000000007294ac)
Location: security/lockdown/lockdown.c:53
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
c000000000729220-c000000000729288: lock_kernel_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/lockdown/lockdown.c (ffffffe0003f409e)
Location: security/lockdown/lockdown.c:53
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffffffe0003f3fe8-ffffffe0003f4036: lock_kernel_down (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff814abde7)
Location: security/lockdown/lockdown.c:53
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffffffff814abd60-ffffffff814abd7c: lock_kernel_down (STB_LOCAL)
ffffffff814abfb9-ffffffff814abfd5: lock_kernel_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff8149c807)
Location: security/lockdown/lockdown.c:53
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffffffff8149c780-ffffffff8149c79c: lock_kernel_down (STB_LOCAL)
ffffffff8149c9d9-ffffffff8149c9f5: lock_kernel_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff814a7e87)
Location: security/lockdown/lockdown.c:53
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffffffff814a7e00-ffffffff814a7e1c: lock_kernel_down (STB_LOCAL)
ffffffff814a8059-ffffffff814a8075: lock_kernel_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/lockdown/lockdown.c (ffffffff814c0817)
Location: security/lockdown/lockdown.c:53
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_write
  - security/lockdown/lockdown.c:lockdown_param
  - security/lockdown/lockdown.c:lockdown_param
```
**Symbols:**

```
ffffffff814c0790-ffffffff814c07ac: lock_kernel_down (STB_LOCAL)
ffffffff814c09e9-ffffffff814c0a05: lock_kernel_down.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
