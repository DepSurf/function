# Function: <code>hv_qlock_wait</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102d160)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff8102d160-ffffffff8102d1ad: hv_qlock_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102ef40)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff8102ef40-ffffffff8102ef8b: hv_qlock_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102f8a0)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff8102f8a0-ffffffff8102f8eb: hv_qlock_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81031fd0)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff81031fd0-ffffffff81032011: hv_qlock_wait.part.0 (STB_LOCAL)
ffffffff81032020-ffffffff81032043: hv_qlock_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81032c30)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff81032c30-ffffffff81032c71: hv_qlock_wait.part.0 (STB_LOCAL)
ffffffff81032c80-ffffffff81032ca3: hv_qlock_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81034740)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff81034740-ffffffff81034789: hv_qlock_wait.part.0 (STB_LOCAL)
ffffffff81034790-ffffffff810347b3: hv_qlock_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff810399e0)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff810399e0-ffffffff81039a29: hv_qlock_wait.part.0 (STB_LOCAL)
ffffffff81039a30-ffffffff81039a53: hv_qlock_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff810408d0)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff810408d0-ffffffff81040929: hv_qlock_wait.part.0 (STB_LOCAL)
ffffffff81040930-ffffffff81040967: hv_qlock_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81049bc0)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff81049bc0-ffffffff81049c20: hv_qlock_wait.part.0 (STB_LOCAL)
ffffffff81049c30-ffffffff81049c67: hv_qlock_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81049df0)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff81049df0-ffffffff81049e50: hv_qlock_wait.part.0 (STB_LOCAL)
ffffffff81049e60-ffffffff81049e97: hv_qlock_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff81051050)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff81051050-ffffffff810510b0: hv_qlock_wait.part.0 (STB_LOCAL)
ffffffff810510c0-ffffffff810510f7: hv_qlock_wait (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102fa00)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff8102fa00-ffffffff8102fa4b: hv_qlock_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8101f3d0)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff8101f3d0-ffffffff8101f422: hv_qlock_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff8102f860)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff8102f860-ffffffff8102f8ab: hv_qlock_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void hv_qlock_wait(u8 *byte, u8 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_spinlock.c (ffffffff810306b0)
Location: arch/x86/hyperv/hv_spinlock.c:26
Inline: True
```
**Symbols:**

```
ffffffff810306b0-ffffffff810306fb: hv_qlock_wait (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
