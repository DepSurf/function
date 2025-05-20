# Function: <code>__sev_es_ist_exit</code>

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
void __sev_es_ist_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81c38290)
Location: arch/x86/kernel/sev-es.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff81c38290-ffffffff81c382ba: __sev_es_ist_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sev_es_ist_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81c2a750)
Location: arch/x86/kernel/sev.c:180
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff81c2a750-ffffffff81c2a77a: __sev_es_ist_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sev_es_ist_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81d48d40)
Location: arch/x86/kernel/sev.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff81d48d40-ffffffff81d48d6a: __sev_es_ist_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sev_es_ist_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81f180a0)
Location: arch/x86/kernel/sev.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff81f180a0-ffffffff81f180da: __sev_es_ist_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sev_es_ist_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff820bf870)
Location: arch/x86/kernel/sev.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff820bf870-ffffffff820bf8aa: __sev_es_ist_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sev_es_ist_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff82141570)
Location: arch/x86/kernel/sev.c:194
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff82141570-ffffffff821415aa: __sev_es_ist_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sev_es_ist_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff82223480)
Location: arch/x86/kernel/sev.c:194
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
**Symbols:**

```
ffffffff82223480-ffffffff822234ba: __sev_es_ist_exit (STB_GLOBAL)
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
