# Function: <code>gnttab_apply</code>

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
int gnttab_apply(pte_t *pte, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81021450)
Location: arch/x86/xen/grant-table.c:94
Inline: False
```
**Symbols:**

```
ffffffff81021450-ffffffff8102146f: gnttab_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gnttab_apply(pte_t *pte, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff810237f0)
Location: arch/x86/xen/grant-table.c:94
Inline: False
```
**Symbols:**

```
ffffffff810237f0-ffffffff8102380f: gnttab_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gnttab_apply(pte_t *pte, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81027a90)
Location: arch/x86/xen/grant-table.c:94
Inline: False
```
**Symbols:**

```
ffffffff81027a90-ffffffff81027aaf: gnttab_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gnttab_apply(pte_t *pte, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8102beb0)
Location: arch/x86/xen/grant-table.c:94
Inline: False
```
**Symbols:**

```
ffffffff8102beb0-ffffffff8102bedb: gnttab_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gnttab_apply(pte_t *pte, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81032db0)
Location: arch/x86/xen/grant-table.c:94
Inline: False
```
**Symbols:**

```
ffffffff81032db0-ffffffff81032ddb: gnttab_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gnttab_apply(pte_t *pte, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81032d50)
Location: arch/x86/xen/grant-table.c:94
Inline: False
```
**Symbols:**

```
ffffffff81032d50-ffffffff81032d7b: gnttab_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gnttab_apply(pte_t *pte, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81039040)
Location: arch/x86/xen/grant-table.c:94
Inline: False
```
**Symbols:**

```
ffffffff81039040-ffffffff8103906b: gnttab_apply (STB_LOCAL)
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
