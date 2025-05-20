# Function: <code>uv_nmi_setup_mmrs</code>

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
In arch/x86/platform/uv/uv_nmi.c (ffffffff828ca0fc)
Location: arch/x86/platform/uv/uv_nmi.c:228
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uv_nmi_setup_mmrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109f586)
Location: arch/x86/platform/uv/uv_nmi.c:228
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
```
**Symbols:**

```
ffffffff8109f586-ffffffff8109f706: uv_nmi_setup_mmrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uv_nmi_setup_mmrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81bda693)
Location: arch/x86/platform/uv/uv_nmi.c:242
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
```
**Symbols:**

```
ffffffff81bda693-ffffffff81bdaa3c: uv_nmi_setup_mmrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uv_nmi_setup_mmrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81bcc7bb)
Location: arch/x86/platform/uv/uv_nmi.c:245
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
```
**Symbols:**

```
ffffffff81bcc7bb-ffffffff81bccaf2: uv_nmi_setup_mmrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uv_nmi_setup_mmrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81ca2bca)
Location: arch/x86/platform/uv/uv_nmi.c:245
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
```
**Symbols:**

```
ffffffff81ca2bca-ffffffff81ca2f40: uv_nmi_setup_mmrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uv_nmi_setup_mmrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81e5247e)
Location: arch/x86/platform/uv/uv_nmi.c:245
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
```
**Symbols:**

```
ffffffff81e5247e-ffffffff81e5271f: uv_nmi_setup_mmrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void uv_nmi_setup_mmrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:245
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
```
**Symbols:**

```
ffffffff810dcfa0-ffffffff810dd2b8: uv_nmi_setup_mmrs (STB_LOCAL)
ffffffff820557df-ffffffff82055817: uv_nmi_setup_mmrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void uv_nmi_setup_mmrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:245
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
```
**Symbols:**

```
ffffffff810e8580-ffffffff810e8898: uv_nmi_setup_mmrs (STB_LOCAL)
ffffffff820d3dda-ffffffff820d3e12: uv_nmi_setup_mmrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void uv_nmi_setup_mmrs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/platform/uv/uv_nmi.c:244
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
```
**Symbols:**

```
ffffffff810f0d90-ffffffff810f10a8: uv_nmi_setup_mmrs (STB_LOCAL)
ffffffff821aec56-ffffffff821aec8e: uv_nmi_setup_mmrs.cold (STB_LOCAL)
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
In arch/x86/platform/uv/uv_nmi.c (ffffffff828cb139)
Location: arch/x86/platform/uv/uv_nmi.c:228
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
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
