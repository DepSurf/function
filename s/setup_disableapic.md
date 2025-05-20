# Function: <code>setup_disableapic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81f70f8a)
Location: arch/x86/kernel/apic/apic.c:2478
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff81f70f8a-ffffffff81f70fac: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81f996bd)
Location: arch/x86/kernel/apic/apic.c:2528
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff81f996bd-ffffffff81f996df: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81fd4b93)
Location: arch/x86/kernel/apic/apic.c:2576
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff81fd4b93-ffffffff81fd4bb5: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff820b585a)
Location: arch/x86/kernel/apic/apic.c:2649
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff820b585a-ffffffff820b5881: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff826bc0d5)
Location: arch/x86/kernel/apic/apic.c:2628
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff826bc0ae-ffffffff826bc0cf: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff826e5efb)
Location: arch/x86/kernel/apic/apic.c:2658
Inline: True
```
**Symbols:**

```
ffffffff826e5efb-ffffffff826e5f1c: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8289ca3c)
Location: arch/x86/kernel/apic/apic.c:2666
Inline: True
```
**Symbols:**

```
ffffffff8289ca3c-ffffffff8289ca5d: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b4851)
Location: arch/x86/kernel/apic/apic.c:2752
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff828b482b-ffffffff828b484c: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b7caa)
Location: arch/x86/kernel/apic/apic.c:2809
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff828b7c84-ffffffff828b7ca5: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff82cdcdcd)
Location: arch/x86/kernel/apic/apic.c:2774
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff82cdcda7-ffffffff82cdcdc8: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff82fc9161)
Location: arch/x86/kernel/apic/apic.c:2845
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff82fc913b-ffffffff82fc915c: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff831d3aa3)
Location: arch/x86/kernel/apic/apic.c:2854
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff831d3a7d-ffffffff831d3a9e: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff832b6607)
Location: arch/x86/kernel/apic/apic.c:2851
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff832b65e1-ffffffff832b6602: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff83468099)
Location: arch/x86/kernel/apic/apic.c:2869
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff8346806d-ffffffff83468094: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff83e8c3f0)
Location: arch/x86/kernel/apic/apic.c:2903
Inline: True
```
**Symbols:**

```
ffffffff83e8c3f0-ffffffff83e8c417: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff836afc00)
Location: arch/x86/kernel/apic/apic.c:2920
Inline: True
```
**Symbols:**

```
ffffffff836afc00-ffffffff836afc27: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff838e0170)
Location: arch/x86/kernel/apic/apic.c:2767
Inline: True
```
**Symbols:**

```
ffffffff838e0170-ffffffff838e0194: setup_disableapic (STB_LOCAL)
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
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828a5cb1)
Location: arch/x86/kernel/apic/apic.c:2809
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff828a5c8b-ffffffff828a5cac: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8289ddf3)
Location: arch/x86/kernel/apic/apic.c:2809
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff8289ddcd-ffffffff8289ddee: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b8bc1)
Location: arch/x86/kernel/apic/apic.c:2809
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff828b8b9b-ffffffff828b8bbc: setup_disableapic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int setup_disableapic(char *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b8cc2)
Location: arch/x86/kernel/apic/apic.c:2809
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nolapic
```
**Symbols:**

```
ffffffff828b8c9c-ffffffff828b8cbd: setup_disableapic (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
