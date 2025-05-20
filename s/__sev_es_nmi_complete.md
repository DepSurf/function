# Function: <code>__sev_es_nmi_complete</code>

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
void __sev_es_nmi_complete();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81c382c0)
Location: arch/x86/kernel/sev-es.c:437
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff81c382c0-ffffffff81c3843c: __sev_es_nmi_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sev_es_nmi_complete();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81c2a780)
Location: arch/x86/kernel/sev.c:516
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff81c2a780-ffffffff81c2a857: __sev_es_nmi_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sev_es_nmi_complete();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81d48d70)
Location: arch/x86/kernel/sev.c:513
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff81d48d70-ffffffff81d48e47: __sev_es_nmi_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sev_es_nmi_complete();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81f180e0)
Location: arch/x86/kernel/sev.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff81f180e0-ffffffff81f181cd: __sev_es_nmi_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sev_es_nmi_complete();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff820bf8c0)
Location: arch/x86/kernel/sev.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff820bf8c0-ffffffff820bf9ad: __sev_es_nmi_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sev_es_nmi_complete();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff821415c0)
Location: arch/x86/kernel/sev.c:555
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff821415c0-ffffffff821416ad: __sev_es_nmi_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sev_es_nmi_complete();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff822234d0)
Location: arch/x86/kernel/sev.c:582
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff822234d0-ffffffff822235bd: __sev_es_nmi_complete (STB_GLOBAL)
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
