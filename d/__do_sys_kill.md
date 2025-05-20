# Function: <code>__do_sys_kill</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __do_sys_kill(pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109fb20)
Location: kernel/signal.c:3167
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff8109fb20-ffffffff8109fcee: __do_sys_kill (STB_LOCAL)
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
In kernel/signal.c (ffffffff810a7f72)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810adcfc)
Location: kernel/signal.c:3634
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810b431c)
Location: kernel/signal.c:3639
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810bd567)
Location: kernel/signal.c:3657
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810b8877)
Location: kernel/signal.c:3677
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810b9df5)
Location: kernel/signal.c:3699
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810cc405)
Location: kernel/signal.c:3787
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810e3640)
Location: kernel/signal.c:3770
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff81103bc0)
Location: kernel/signal.c:3772
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff8110fe00)
Location: kernel/signal.c:3796
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff81119770)
Location: kernel/signal.c:3807
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffff8000101101ec)
Location: kernel/signal.c:3639
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_kill
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
In kernel/signal.c (c03695d4)
Location: kernel/signal.c:3639
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
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
In kernel/signal.c (c000000000157950)
Location: kernel/signal.c:3639
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
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
In kernel/signal.c (ffffffe0000d15e0)
Location: kernel/signal.c:3639
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
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
In kernel/signal.c (ffffffff810ae68c)
Location: kernel/signal.c:3639
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff8109cfdc)
Location: kernel/signal.c:3639
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810adbec)
Location: kernel/signal.c:3639
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810b5e4c)
Location: kernel/signal.c:3639
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
