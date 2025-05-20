# Function: <code>pci_mmcfg_arch_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff816f6840)
Location: arch/x86/pci/mmconfig_64.c:136
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff816f6840-ffffffff816f68ae: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff8175b4b0)
Location: arch/x86/pci/mmconfig_64.c:136
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff8175b4b0-ffffffff8175b51e: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff81787a20)
Location: arch/x86/pci/mmconfig_64.c:136
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff81787a20-ffffffff81787a8e: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff817a6b50)
Location: arch/x86/pci/mmconfig_64.c:136
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff817a6b50-ffffffff817a6bbe: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff8181ddb0)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff8181ddb0-ffffffff8181de1e: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (0)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff818680a9-ffffffff818680c3: pci_mmcfg_arch_map.cold.0 (STB_LOCAL)
ffffffff81868010-ffffffff8186806d: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (0)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff81888129-ffffffff81888143: pci_mmcfg_arch_map.cold.0 (STB_LOCAL)
ffffffff81888090-ffffffff818880ed: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (0)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff818d2a28-ffffffff818d2a4a: pci_mmcfg_arch_map.cold (STB_LOCAL)
ffffffff818d2990-ffffffff818d29e4: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (0)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff81904dd8-ffffffff81904dfa: pci_mmcfg_arch_map.cold (STB_LOCAL)
ffffffff81904d40-ffffffff81904d94: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (0)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff81bb539b-ffffffff81bb53bd: pci_mmcfg_arch_map.cold (STB_LOCAL)
ffffffff81bb5300-ffffffff81bb5357: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (0)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff81c3401b-ffffffff81c3403d: pci_mmcfg_arch_map.cold (STB_LOCAL)
ffffffff81bca500-ffffffff81bca557: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff81bbde60)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff81bbde60-ffffffff81bbdece: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff81c8dda0)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff81c8dda0-ffffffff81c8de0e: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff81e3cd30)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff81e3cd30-ffffffff81e3cda8: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff83f13de2)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff82016010-ffffffff82016088: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff8373a562)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff820963f0-ffffffff82096468: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (ffffffff8396ede2)
Location: arch/x86/pci/mmconfig_64.c:114
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff8216d900-ffffffff8216d978: pci_mmcfg_arch_map (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (0)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff818a4208-ffffffff818a422a: pci_mmcfg_arch_map.cold (STB_LOCAL)
ffffffff818a4170-ffffffff818a41c4: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (0)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff8185f978-ffffffff8185f99a: pci_mmcfg_arch_map.cold (STB_LOCAL)
ffffffff8185f8e0-ffffffff8185f934: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (0)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff818f57f8-ffffffff818f581a: pci_mmcfg_arch_map.cold (STB_LOCAL)
ffffffff818f5760-ffffffff818f57b4: pci_mmcfg_arch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_mmcfg_arch_map(struct pci_mmcfg_region *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/mmconfig_64.c (0)
Location: arch/x86/pci/mmconfig_64.c:137
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff819168e8-ffffffff8191690a: pci_mmcfg_arch_map.cold (STB_LOCAL)
ffffffff81916850-ffffffff819168a4: pci_mmcfg_arch_map (STB_GLOBAL)
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
