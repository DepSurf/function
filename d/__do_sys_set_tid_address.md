# Function: <code>__do_sys_set_tid_address</code>

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
In kernel/fork.c (ffffffff8108a9c5)
Location: kernel/fork.c:1547
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffffffff81092965)
Location: kernel/fork.c:1605
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffffffff81096825)
Location: kernel/fork.c:1632
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffffffff8109cef5)
Location: kernel/fork.c:1632
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffffffff810a3af5)
Location: kernel/fork.c:1652
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffffffff8109f248)
Location: kernel/fork.c:1649
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffffffff810a0118)
Location: kernel/fork.c:1648
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffffffff810b1528)
Location: kernel/fork.c:1727
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffffffff810c7828)
Location: kernel/fork.c:1772
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffffffff810e4388)
Location: kernel/fork.c:1793
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffffffff810efa18)
Location: kernel/fork.c:1941
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffffffff810f8e28)
Location: kernel/fork.c:1938
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffff8000100f11b8)
Location: kernel/fork.c:1632
Inline: True
Inline callers:
  - kernel/fork.c:__arm64_sys_set_tid_address
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
In kernel/fork.c (c0353250)
Location: kernel/fork.c:1632
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_set_tid_address
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
In kernel/fork.c (c000000000136d1c)
Location: kernel/fork.c:1632
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_set_tid_address
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
In kernel/fork.c (ffffffe0000c125c)
Location: kernel/fork.c:1632
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_set_tid_address
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
In kernel/fork.c (ffffffff81096815)
Location: kernel/fork.c:1632
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffffffff81085295)
Location: kernel/fork.c:1632
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffffffff810967c5)
Location: kernel/fork.c:1632
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
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
In kernel/fork.c (ffffffff8109e655)
Location: kernel/fork.c:1632
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_set_tid_address
  - kernel/fork.c:__x64_sys_set_tid_address
```
</details>
</li>
</ul>

## Differences
