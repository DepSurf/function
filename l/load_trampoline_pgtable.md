# Function: <code>load_trampoline_pgtable</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void load_trampoline_pgtable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff81039a70)
Location: arch/x86/realmode/init.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
**Symbols:**

```
ffffffff81039a70-ffffffff81039acf: load_trampoline_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void load_trampoline_pgtable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff810409d0)
Location: arch/x86/realmode/init.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
**Symbols:**

```
ffffffff810409d0-ffffffff81040a1f: load_trampoline_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void load_trampoline_pgtable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff81049d00)
Location: arch/x86/realmode/init.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
**Symbols:**

```
ffffffff81049d00-ffffffff81049d4f: load_trampoline_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void load_trampoline_pgtable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff81049f30)
Location: arch/x86/realmode/init.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
**Symbols:**

```
ffffffff81049f30-ffffffff81049f7f: load_trampoline_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void load_trampoline_pgtable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff81051190)
Location: arch/x86/realmode/init.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
**Symbols:**

```
ffffffff81051190-ffffffff810511df: load_trampoline_pgtable (STB_GLOBAL)
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
