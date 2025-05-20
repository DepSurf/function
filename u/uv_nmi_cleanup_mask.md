# Function: <code>uv_nmi_cleanup_mask</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:562
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uv_nmi_cleanup_mask();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ecb0)
Location: arch/x86/platform/uv/uv_nmi.c:562
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff8109ecb0-ffffffff8109ed15: uv_nmi_cleanup_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uv_nmi_cleanup_mask();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a7f0)
Location: arch/x86/platform/uv/uv_nmi.c:604
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff8109a7f0-ffffffff8109a855: uv_nmi_cleanup_mask (STB_LOCAL)
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
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b54f)
Location: arch/x86/platform/uv/uv_nmi.c:607
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
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
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:607
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
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
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:608
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
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
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:608
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
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
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:608
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
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
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:607
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
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
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:562
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
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
</ul>
