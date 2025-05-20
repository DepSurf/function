# Function: <code>__do_compat_sys_kexec_load</code>

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
In kernel/kexec.c (ffffffff811386ce)
Location: kernel/kexec.c:258
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
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
In kernel/kexec.c (ffffffff81143f4e)
Location: kernel/kexec.c:266
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
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
In kernel/kexec.c (ffffffff8114f2ae)
Location: kernel/kexec.c:264
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
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
In kernel/kexec.c (ffffffff8115afae)
Location: kernel/kexec.c:265
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
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
In kernel/kexec.c (ffffffff8116be1e)
Location: kernel/kexec.c:269
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
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
In kernel/kexec.c (ffffffff8116850e)
Location: kernel/kexec.c:269
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
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
In kernel/kexec.c (ffffffff811692ae)
Location: kernel/kexec.c:269
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_kexec_load(compat_ulong_t entry, compat_ulong_t nr_segments, struct compat_kexec_segment *segments, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff8118ec10)
Location: kernel/kexec.c:257
Inline: False
Direct callers:
  - kernel/kexec.c:__x64_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
**Symbols:**

```
ffffffff8118ec10-ffffffff8118ed8b: __do_compat_sys_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_kexec_load(compat_ulong_t entry, compat_ulong_t nr_segments, struct compat_kexec_segment *segments, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff811be320)
Location: kernel/kexec.c:257
Inline: False
Direct callers:
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
**Symbols:**

```
ffffffff811be320-ffffffff811be4b7: __do_compat_sys_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_kexec_load(compat_ulong_t entry, compat_ulong_t nr_segments, struct compat_kexec_segment *segments, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff81200410)
Location: kernel/kexec.c:254
Inline: False
Direct callers:
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
**Symbols:**

```
ffffffff81200410-ffffffff812005a7: __do_compat_sys_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_kexec_load(compat_ulong_t entry, compat_ulong_t nr_segments, struct compat_kexec_segment *segments, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff81215870)
Location: kernel/kexec.c:256
Inline: False
Direct callers:
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
**Symbols:**

```
ffffffff81215870-ffffffff812159ef: __do_compat_sys_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_kexec_load(compat_ulong_t entry, compat_ulong_t nr_segments, struct compat_kexec_segment *segments, compat_ulong_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff8122d820)
Location: kernel/kexec.c:261
Inline: False
Direct callers:
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
**Symbols:**

```
ffffffff8122d820-ffffffff8122d99f: __do_compat_sys_kexec_load (STB_LOCAL)
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
In kernel/kexec.c (ffff8000101ca448)
Location: kernel/kexec.c:265
Inline: True
Inline callers:
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (c000000000232e78)
Location: kernel/kexec.c:265
Inline: True
Inline callers:
  - kernel/kexec.c:__se_compat_sys_kexec_load
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/kexec.c (ffffffff811535ce)
Location: kernel/kexec.c:265
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
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
In kernel/kexec.c (ffffffff811468ee)
Location: kernel/kexec.c:265
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
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
In kernel/kexec.c (ffffffff8115147e)
Location: kernel/kexec.c:265
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
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
In kernel/kexec.c (ffffffff8115e29e)
Location: kernel/kexec.c:265
Inline: True
Inline callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
