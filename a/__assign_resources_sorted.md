# Function: <code>__assign_resources_sorted</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8143e9c0)
Location: drivers/pci/setup-bus.c:363
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff8143e9c0-ffffffff8143ef17: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8148a810)
Location: drivers/pci/setup-bus.c:362
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8148a810-ffffffff8148ad88: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814ac000)
Location: drivers/pci/setup-bus.c:363
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff814ac000-ffffffff814ac578: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814b6330)
Location: drivers/pci/setup-bus.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff814b6330-ffffffff814b68d9: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f5ff0)
Location: drivers/pci/setup-bus.c:354
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff814f5ff0-ffffffff814f6599: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81526ce0)
Location: drivers/pci/setup-bus.c:349
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81526ce0-ffffffff81527295: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8153cb80)
Location: drivers/pci/setup-bus.c:349
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8153cb80-ffffffff8153d135: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:343
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8156c230-ffffffff8156c76d: __assign_resources_sorted (STB_LOCAL)
ffffffff8156ea3e-ffffffff8156ea60: __assign_resources_sorted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:343
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8158d210-ffffffff8158d74d: __assign_resources_sorted (STB_LOCAL)
ffffffff8158fa11-ffffffff8158fa33: __assign_resources_sorted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81635270)
Location: drivers/pci/setup-bus.c:344
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81635270-ffffffff81635932: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8165a330)
Location: drivers/pci/setup-bus.c:345
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8165a330-ffffffff8165a9f2: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:345
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8163c770-ffffffff8163cf31: __assign_resources_sorted (STB_LOCAL)
ffffffff81bea812-ffffffff81bea836: __assign_resources_sorted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:345
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff816ad1d0-ffffffff816ad991: __assign_resources_sorted (STB_LOCAL)
ffffffff81ce5694-ffffffff81ce56b8: __assign_resources_sorted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:345
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff817d0650-ffffffff817d0e1a: __assign_resources_sorted (STB_LOCAL)
ffffffff81eac15e-ffffffff81eac17f: __assign_resources_sorted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818f09d0)
Location: drivers/pci/setup-bus.c:345
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff818f09d0-ffffffff818f11b6: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81933df0)
Location: drivers/pci/setup-bus.c:342
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81933df0-ffffffff819345d3: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197cb70)
Location: drivers/pci/setup-bus.c:345
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8197cb70-ffffffff8197d2f5: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f24f8)
Location: drivers/pci/setup-bus.c:343
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffff8000106f24f8-ffff8000106f2a50: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088cf7c)
Location: drivers/pci/setup-bus.c:343
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
c088cf7c-c088d544: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c000000000870180)
Location: drivers/pci/setup-bus.c:343
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
c000000000870180-c0000000008708b0: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c5914)
Location: drivers/pci/setup-bus.c:343
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffe0004c5914-ffffffe0004c5d94: __assign_resources_sorted (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:343
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81581090-ffffffff815815cd: __assign_resources_sorted (STB_LOCAL)
ffffffff81583895-ffffffff815838b7: __assign_resources_sorted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:343
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8156fe70-ffffffff815703ad: __assign_resources_sorted (STB_LOCAL)
ffffffff81572671-ffffffff81572693: __assign_resources_sorted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:343
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81580f60-ffffffff8158149d: __assign_resources_sorted (STB_LOCAL)
ffffffff81583761-ffffffff81583783: __assign_resources_sorted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __assign_resources_sorted(struct list_head *head, struct list_head *realloc_head, struct list_head *fail_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:343
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8159b410-ffffffff8159b94d: __assign_resources_sorted (STB_LOCAL)
ffffffff8159dc11-ffffffff8159dc33: __assign_resources_sorted.cold (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
