# Function: <code>uncore_types_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int uncore_types_init(struct intel_uncore_type **types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81f5ff6f)
Location: arch/x86/events/intel/uncore.c:839
Inline: False
```
**Symbols:**

```
ffffffff81f5ff6f-ffffffff81f60113: uncore_types_init (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff81f87e3c)
Location: arch/x86/events/intel/uncore.c:870
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff81fc32b6)
Location: arch/x86/events/intel/uncore.c:856
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff820a3547)
Location: arch/x86/events/intel/uncore.c:856
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff826a9861)
Location: arch/x86/events/intel/uncore.c:864
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff826d2a02)
Location: arch/x86/events/intel/uncore.c:925
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff82888d1e)
Location: arch/x86/events/intel/uncore.c:926
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int uncore_types_init(struct intel_uncore_type **types, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8289fc9e)
Location: arch/x86/events/intel/uncore.c:936
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8289fc9e-ffffffff8289fe7a: uncore_types_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int uncore_types_init(struct intel_uncore_type **types, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff828a2d70)
Location: arch/x86/events/intel/uncore.c:968
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff828a2d70-ffffffff828a2f56: uncore_types_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uncore_types_init(struct intel_uncore_type **types, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff82cc8fdd)
Location: arch/x86/events/intel/uncore.c:968
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff82cc8fdd-ffffffff82cc9011: uncore_types_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uncore_types_init(struct intel_uncore_type **types, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff82fb4e1b)
Location: arch/x86/events/intel/uncore.c:981
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff82fb4e1b-ffffffff82fb4e4f: uncore_types_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uncore_types_init(struct intel_uncore_type **types, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff831bf395)
Location: arch/x86/events/intel/uncore.c:1021
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff831bf395-ffffffff831bf3c9: uncore_types_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uncore_types_init(struct intel_uncore_type **types, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8329f805)
Location: arch/x86/events/intel/uncore.c:1028
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff8329f805-ffffffff8329f839: uncore_types_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uncore_types_init(struct intel_uncore_type **types, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8344e606)
Location: arch/x86/events/intel/uncore.c:1028
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff8344e606-ffffffff8344e642: uncore_types_init (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff83e6a0cd)
Location: arch/x86/events/intel/uncore.c:1028
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
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
In arch/x86/events/intel/uncore.c (ffffffff8368aa56)
Location: arch/x86/events/intel/uncore.c:1049
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
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
In arch/x86/events/intel/uncore.c (ffffffff838ba616)
Location: arch/x86/events/intel/uncore.c:1049
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
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
<summary>In <code>aws</code>: ✅</summary>

```c
int uncore_types_init(struct intel_uncore_type **types, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff82890d70)
Location: arch/x86/events/intel/uncore.c:968
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff82890d70-ffffffff82890f56: uncore_types_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int uncore_types_init(struct intel_uncore_type **types, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8288ec55)
Location: arch/x86/events/intel/uncore.c:968
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8288ec55-ffffffff8288ee3b: uncore_types_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int uncore_types_init(struct intel_uncore_type **types, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff828a3d70)
Location: arch/x86/events/intel/uncore.c:968
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff828a3d70-ffffffff828a3f56: uncore_types_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uncore_types_init(struct intel_uncore_type **types, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff828a3d84)
Location: arch/x86/events/intel/uncore.c:968
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff828a3d84-ffffffff828a3f6a: uncore_types_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
