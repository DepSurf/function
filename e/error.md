# Function: <code>error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void error(char *x);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts_rd.c (ffffffff81f5a957)
Location: init/do_mounts_rd.c:338
Inline: False
```
```
In init/initramfs.c (ffffffff81f5bacd)
Location: init/initramfs.c:46
Inline: False
Direct callers:
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff81f5a957-ffffffff81f5a976: error (STB_LOCAL)
ffffffff81f5bacd-ffffffff81f5bae4: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void error(char *x);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts_rd.c (ffffffff81f82911)
Location: init/do_mounts_rd.c:331
Inline: False
```
```
In init/initramfs.c (ffffffff81f83a6a)
Location: init/initramfs.c:46
Inline: False
Direct callers:
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff81f82911-ffffffff81f82930: error (STB_LOCAL)
ffffffff81f83a6a-ffffffff81f83a81: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff81fbf07f)
Location: init/initramfs.c:46
Inline: False
Direct callers:
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff81fbf07f-ffffffff81fbf096: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8209f1b1)
Location: init/initramfs.c:47
Inline: False
Direct callers:
  - init/initramfs.c:flush_buffer
```
**Symbols:**

```
ffffffff8209f1b1-ffffffff8209f1cd: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff826a51ae)
Location: init/initramfs.c:48
Inline: False
Direct callers:
  - init/initramfs.c:flush_buffer
```
**Symbols:**

```
ffffffff826a51ae-ffffffff826a51ca: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff826ce362)
Location: init/initramfs.c:48
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff826ce362-ffffffff826ce37e: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff828843a5)
Location: init/initramfs.c:38
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff828843a5-ffffffff828843c1: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289b3f6)
Location: init/initramfs.c:38
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff8289b3f6-ffffffff8289b412: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289e3db)
Location: init/initramfs.c:38
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff8289e3db-ffffffff8289e3f7: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff82cc48ec)
Location: init/initramfs.c:39
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff82cc48ec-ffffffff82cc4908: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff82fb0221)
Location: init/initramfs.c:42
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff82fb0221-ffffffff82fb023d: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff831ba284)
Location: init/initramfs.c:44
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff831ba284-ffffffff831ba2a0: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8329a742)
Location: init/initramfs.c:45
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff8329a742-ffffffff8329a75e: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff83448a5c)
Location: init/initramfs.c:56
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff83448a5c-ffffffff83448a7e: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff83e63847)
Location: init/initramfs.c:56
Inline: True
Inline callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff83e62a00-ffffffff83e62a2a: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff83683e67)
Location: init/initramfs.c:57
Inline: True
Inline callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff83682fb0-ffffffff83682fda: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff838b2fd5)
Location: init/initramfs.c:57
Inline: True
Inline callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff838b2090-ffffffff838b20ba: error (STB_LOCAL)
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
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffff800011432568)
Location: init/initramfs.c:38
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffff800011432568-ffff80001143259c: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (c15025dc)
Location: init/initramfs.c:38
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
c15025dc-c1502608: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (c000000001345da0)
Location: init/initramfs.c:38
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
c000000001345da0-c000000001345dcc: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffe00000216c)
Location: init/initramfs.c:38
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffe00000216c-ffffffe00000219a: error (STB_LOCAL)
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
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8288c3db)
Location: init/initramfs.c:38
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff8288c3db-ffffffff8288c3f7: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8288a358)
Location: init/initramfs.c:38
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff8288a358-ffffffff8288a374: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289f3db)
Location: init/initramfs.c:38
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff8289f3db-ffffffff8289f3f7: error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void error(char *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289f3e0)
Location: init/initramfs.c:38
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:flush_buffer
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_reset
  - init/initramfs.c:do_header
  - init/initramfs.c:do_header
```
**Symbols:**

```
ffffffff8289f3e0-ffffffff8289f3fc: error (STB_LOCAL)
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
