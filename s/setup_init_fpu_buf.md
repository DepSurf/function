# Function: <code>setup_init_fpu_buf</code>

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
In arch/x86/kernel/fpu/xstate.c (ffffffff81f6a020)
Location: arch/x86/kernel/fpu/xstate.c:298
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81f92120)
Location: arch/x86/kernel/fpu/xstate.c:410
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81fcd3d0)
Location: arch/x86/kernel/fpu/xstate.c:415
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff820ada94)
Location: arch/x86/kernel/fpu/xstate.c:416
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff826b402b)
Location: arch/x86/kernel/fpu/xstate.c:410
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff826dd801)
Location: arch/x86/kernel/fpu/xstate.c:410
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff82893c49)
Location: arch/x86/kernel/fpu/xstate.c:410
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void setup_init_fpu_buf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff828ab0b8)
Location: arch/x86/kernel/fpu/xstate.c:404
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff828ab0b8-ffffffff828ab2ef: setup_init_fpu_buf (STB_LOCAL)
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
In arch/x86/kernel/fpu/xstate.c (ffffffff828ae3f6)
Location: arch/x86/kernel/fpu/xstate.c:404
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void setup_init_fpu_buf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff82cd3450)
Location: arch/x86/kernel/fpu/xstate.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff82cd3450-ffffffff82cd3573: setup_init_fpu_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void setup_init_fpu_buf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff82fbf20a)
Location: arch/x86/kernel/fpu/xstate.c:446
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff82fbf20a-ffffffff82fbf33f: setup_init_fpu_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void setup_init_fpu_buf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff831c96bb)
Location: arch/x86/kernel/fpu/xstate.c:465
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff831c96bb-ffffffff831c98a7: setup_init_fpu_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void setup_init_fpu_buf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff832aa988)
Location: arch/x86/kernel/fpu/xstate.c:380
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff832aa988-ffffffff832aabf3: setup_init_fpu_buf (STB_LOCAL)
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8345ae10)
Location: arch/x86/kernel/fpu/xstate.c:352
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void setup_init_fpu_buf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff83e79e60)
Location: arch/x86/kernel/fpu/xstate.c:352
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff83e79e60-ffffffff83e79f64: setup_init_fpu_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void setup_init_fpu_buf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8369c580)
Location: arch/x86/kernel/fpu/xstate.c:352
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff8369c580-ffffffff8369c684: setup_init_fpu_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void setup_init_fpu_buf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff838cc270)
Location: arch/x86/kernel/fpu/xstate.c:355
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff838cc270-ffffffff838cc37e: setup_init_fpu_buf (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8289c415)
Location: arch/x86/kernel/fpu/xstate.c:404
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff82894633)
Location: arch/x86/kernel/fpu/xstate.c:404
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff828af3d8)
Location: arch/x86/kernel/fpu/xstate.c:404
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff828af406)
Location: arch/x86/kernel/fpu/xstate.c:404
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
