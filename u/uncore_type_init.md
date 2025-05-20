# Function: <code>uncore_type_init</code>

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
In arch/x86/events/intel/uncore.c (ffffffff81f5ff93)
Location: arch/x86/events/intel/uncore.c:785
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type *type, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81f87c55)
Location: arch/x86/events/intel/uncore.c:819
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff81f87c55-ffffffff81f87db4: uncore_type_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type *type, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81fc30cf)
Location: arch/x86/events/intel/uncore.c:805
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff81fc30cf-ffffffff81fc322e: uncore_type_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type *type, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff820a335c)
Location: arch/x86/events/intel/uncore.c:805
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff820a335c-ffffffff820a34ba: uncore_type_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type *type, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff826a9646)
Location: arch/x86/events/intel/uncore.c:805
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff826a9646-ffffffff826a97d4: uncore_type_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type *type, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff826d27cb)
Location: arch/x86/events/intel/uncore.c:865
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff826d27cb-ffffffff826d297c: uncore_type_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type *type, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff82888adb)
Location: arch/x86/events/intel/uncore.c:866
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff82888adb-ffffffff82888c98: uncore_type_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8289fcc6)
Location: arch/x86/events/intel/uncore.c:876
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
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
In arch/x86/events/intel/uncore.c (ffffffff828a2d98)
Location: arch/x86/events/intel/uncore.c:908
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type *type, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff82cc8e13)
Location: arch/x86/events/intel/uncore.c:908
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
**Symbols:**

```
ffffffff82cc8e13-ffffffff82cc8fdd: uncore_type_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type *type, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff82fb4c2d)
Location: arch/x86/events/intel/uncore.c:918
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
**Symbols:**

```
ffffffff82fb4c2d-ffffffff82fb4e1b: uncore_type_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type *type, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff831bf19e)
Location: arch/x86/events/intel/uncore.c:958
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
**Symbols:**

```
ffffffff831bf19e-ffffffff831bf395: uncore_type_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type *type, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8329f5ec)
Location: arch/x86/events/intel/uncore.c:965
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
**Symbols:**

```
ffffffff8329f5ec-ffffffff8329f805: uncore_type_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type *type, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8344e3f0)
Location: arch/x86/events/intel/uncore.c:965
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
**Symbols:**

```
ffffffff8344e3f0-ffffffff8344e606: uncore_type_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type *type, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff83e699c0)
Location: arch/x86/events/intel/uncore.c:965
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff83e699c0-ffffffff83e69c19: uncore_type_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type *type, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8368a350)
Location: arch/x86/events/intel/uncore.c:986
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff8368a350-ffffffff8368a5aa: uncore_type_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type *type, bool setid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff838b9f10)
Location: arch/x86/events/intel/uncore.c:986
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff838b9f10-ffffffff838ba16a: uncore_type_init (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff82890d98)
Location: arch/x86/events/intel/uncore.c:908
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
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
In arch/x86/events/intel/uncore.c (ffffffff8288ec7d)
Location: arch/x86/events/intel/uncore.c:908
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
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
In arch/x86/events/intel/uncore.c (ffffffff828a3d98)
Location: arch/x86/events/intel/uncore.c:908
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
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
In arch/x86/events/intel/uncore.c (ffffffff828a3dac)
Location: arch/x86/events/intel/uncore.c:908
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_types_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
