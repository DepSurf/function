# Function: <code>hv_stimer_setup_percpu_clockev</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hv_stimer_setup_percpu_clockev();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff82fba67c)
Location: arch/x86/hyperv/hv_init.c:328
Inline: False
```
**Symbols:**

```
ffffffff82fba67c-ffffffff82fba69a: hv_stimer_setup_percpu_clockev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hv_stimer_setup_percpu_clockev();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff831c4d0b)
Location: arch/x86/hyperv/hv_init.c:332
Inline: False
```
**Symbols:**

```
ffffffff831c4d0b-ffffffff831c4d2b: hv_stimer_setup_percpu_clockev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hv_stimer_setup_percpu_clockev();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff832a5a10)
Location: arch/x86/hyperv/hv_init.c:314
Inline: False
```
**Symbols:**

```
ffffffff832a5a10-ffffffff832a5a30: hv_stimer_setup_percpu_clockev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hv_stimer_setup_percpu_clockev();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff83454aa5)
Location: arch/x86/hyperv/hv_init.c:354
Inline: False
```
**Symbols:**

```
ffffffff83454aa5-ffffffff83454acd: hv_stimer_setup_percpu_clockev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hv_stimer_setup_percpu_clockev();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff83e72630)
Location: arch/x86/hyperv/hv_init.c:344
Inline: False
```
**Symbols:**

```
ffffffff83e72630-ffffffff83e72658: hv_stimer_setup_percpu_clockev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hv_stimer_setup_percpu_clockev();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff83693550)
Location: arch/x86/hyperv/hv_init.c:347
Inline: False
```
**Symbols:**

```
ffffffff83693550-ffffffff83693578: hv_stimer_setup_percpu_clockev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hv_stimer_setup_percpu_clockev();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff838c30d0)
Location: arch/x86/hyperv/hv_init.c:381
Inline: False
```
**Symbols:**

```
ffffffff838c30d0-ffffffff838c30f8: hv_stimer_setup_percpu_clockev (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
