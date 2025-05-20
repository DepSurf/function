# Function: <code>put_uts_ns</code>

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
In kernel/nsproxy.c (ffffffff810a1011)
Location: include/linux/utsname.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/utsname.c (ffffffff8111dbc5)
Location: include/linux/utsname.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810a4856)
Location: include/linux/utsname.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff81125b27)
Location: include/linux/utsname.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810aa4b6)
Location: include/linux/utsname.h:42
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff8112f537)
Location: include/linux/utsname.h:42
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810a7034)
Location: include/linux/utsname.h:42
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff81130d39)
Location: include/linux/utsname.h:42
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810ad7b4)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff8113dc8f)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810b4514)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff8114c62f)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810bd664)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff8115924f)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810c36b6)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff8116598f)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810cc7c6)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff8117184f)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810d5d46)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff81183638)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810d0916)
Location: include/linux/utsname.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff8118056e)
Location: include/linux/utsname.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810d24f6)
Location: include/linux/utsname.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff811815ce)
Location: include/linux/utsname.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810e5636)
Location: include/linux/utsname.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff811a953e)
Location: include/linux/utsname.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810ff444)
Location: include/linux/utsname.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff811da882)
Location: include/linux/utsname.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff81124164)
Location: include/linux/utsname.h:42
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff8121fe92)
Location: include/linux/utsname.h:42
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff81131464)
Location: include/linux/utsname.h:42
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff81236082)
Location: include/linux/utsname.h:42
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff8113c1f4)
Location: include/linux/utsname.h:42
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff8124fd02)
Location: include/linux/utsname.h:42
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffff80001012b50c)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffff8000101e5464)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (c037bab0)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (c0425ce0)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (c000000000173f94)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (c0000000002558bc)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffe0000e033e)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffe00015aef8)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810c6b46)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff81169e6f)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810b5366)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff8115d06f)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810c6096)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff81167c3f)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
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
In kernel/nsproxy.c (ffffffff810ce4e6)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/utsname.c (ffffffff8117531f)
Location: include/linux/utsname.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
```
</details>
</li>
</ul>

## Differences
