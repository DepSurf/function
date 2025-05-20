# Function: <code>do_kexec_load</code>

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
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff811156e0)
Location: kernel/kexec.c:108
Inline: False
Direct callers:
  - kernel/kexec.c:compat_SyS_kexec_load
```
**Symbols:**

```
ffffffff811156e0-ffffffff8111593e: do_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff8111ce00)
Location: kernel/kexec.c:108
Inline: False
Direct callers:
  - kernel/kexec.c:compat_SyS_kexec_load
```
**Symbols:**

```
ffffffff8111ce00-ffffffff8111d05e: do_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff8111ea30)
Location: kernel/kexec.c:107
Inline: False
Direct callers:
  - kernel/kexec.c:compat_SyS_kexec_load
```
**Symbols:**

```
ffffffff8111ea30-ffffffff8111eca0: do_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff8112a190)
Location: kernel/kexec.c:107
Inline: False
Direct callers:
  - kernel/kexec.c:compat_SyS_kexec_load
```
**Symbols:**

```
ffffffff8112a190-ffffffff8112a400: do_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:107
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff811380f0-ffffffff81138328: do_kexec_load (STB_LOCAL)
ffffffff8113882e-ffffffff81138878: do_kexec_load.cold.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:108
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff81143910-ffffffff81143b48: do_kexec_load (STB_LOCAL)
ffffffff811440c7-ffffffff81144111: do_kexec_load.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:106
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff8114ec70-ffffffff8114eea1: do_kexec_load (STB_LOCAL)
ffffffff8114f429-ffffffff8114f473: do_kexec_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:106
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff8115a980-ffffffff8115abd1: do_kexec_load (STB_LOCAL)
ffffffff8115b112-ffffffff8115b15c: do_kexec_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff8116b8c0)
Location: kernel/kexec.c:106
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff8116b8c0-ffffffff8116ba48: do_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff81167fb0)
Location: kernel/kexec.c:106
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff81167fb0-ffffffff81168138: do_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff81168d50)
Location: kernel/kexec.c:106
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff81168d50-ffffffff81168ed7: do_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:87
Inline: False
Direct callers:
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff8118e970-ffffffff8118ec02: do_kexec_load (STB_LOCAL)
ffffffff81cb2c9f-ffffffff81cb2ce9: do_kexec_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff811be120)
Location: kernel/kexec.c:87
Inline: False
Direct callers:
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff811be120-ffffffff811be31b: do_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff81200200)
Location: kernel/kexec.c:87
Inline: False
Direct callers:
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff81200200-ffffffff812003f7: do_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff81215660)
Location: kernel/kexec.c:87
Inline: False
Direct callers:
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff81215660-ffffffff81215857: do_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff8122d600)
Location: kernel/kexec.c:87
Inline: False
Direct callers:
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff8122d600-ffffffff8122d804: do_kexec_load (STB_LOCAL)
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
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffff8000101ca038)
Location: kernel/kexec.c:106
Inline: False
Direct callers:
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
  - kernel/kexec.c:__arm64_sys_kexec_load
```
**Symbols:**

```
ffff8000101ca038-ffff8000101ca30c: do_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (c0410e1c)
Location: kernel/kexec.c:106
Inline: False
Direct callers:
  - kernel/kexec.c:__se_sys_kexec_load
```
**Symbols:**

```
c0410e1c-c04111d4: do_kexec_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (c000000000232a00)
Location: kernel/kexec.c:106
Inline: False
Direct callers:
  - kernel/kexec.c:__se_compat_sys_kexec_load
  - kernel/kexec.c:__se_sys_kexec_load
```
**Symbols:**

```
c000000000232a00-c000000000232e24: do_kexec_load (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:106
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff81152fa0-ffffffff811531f1: do_kexec_load (STB_LOCAL)
ffffffff81153732-ffffffff8115377c: do_kexec_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:106
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff811462c0-ffffffff81146511: do_kexec_load (STB_LOCAL)
ffffffff81146a52-ffffffff81146a9c: do_kexec_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:106
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff81150e50-ffffffff811510a1: do_kexec_load (STB_LOCAL)
ffffffff811515e2-ffffffff8115162c: do_kexec_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment *segments, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec.c (0)
Location: kernel/kexec.c:106
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
**Symbols:**

```
ffffffff8115dc70-ffffffff8115dec1: do_kexec_load (STB_LOCAL)
ffffffff8115e402-ffffffff8115e44c: do_kexec_load.cold (STB_LOCAL)
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
