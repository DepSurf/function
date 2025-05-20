# Function: <code>free_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8143e630)
Location: drivers/pci/setup-bus.c:44
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
**Symbols:**

```
ffffffff8143e630-ffffffff8143e68b: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8148a490)
Location: drivers/pci/setup-bus.c:43
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8148a490-ffffffff8148a4f6: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814abc80)
Location: drivers/pci/setup-bus.c:44
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff814abc80-ffffffff814abce6: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814b5fc0)
Location: drivers/pci/setup-bus.c:44
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff814b5fc0-ffffffff814b6027: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f59c0)
Location: drivers/pci/setup-bus.c:44
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff814f59c0-ffffffff814f5a27: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff815266b0)
Location: drivers/pci/setup-bus.c:41
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff815266b0-ffffffff81526717: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8153c5d0)
Location: drivers/pci/setup-bus.c:41
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8153c5d0-ffffffff8153c637: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8156bd30)
Location: drivers/pci/setup-bus.c:41
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8156bd30-ffffffff8156bd8d: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8158cd10)
Location: drivers/pci/setup-bus.c:41
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8158cd10-ffffffff8158cd6d: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81636ff9)
Location: drivers/pci/setup-bus.c:42
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
**Symbols:**

```
ffffffff81633c90-ffffffff81633ced: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8165c0b9)
Location: drivers/pci/setup-bus.c:42
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
**Symbols:**

```
ffffffff81658d40-ffffffff81658d9d: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8163e659)
Location: drivers/pci/setup-bus.c:42
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
**Symbols:**

```
ffffffff8163b390-ffffffff8163b3ed: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff816af1db)
Location: drivers/pci/setup-bus.c:42
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
**Symbols:**

```
ffffffff816abdc0-ffffffff816abe1d: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff817d2675)
Location: drivers/pci/setup-bus.c:42
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
**Symbols:**

```
ffffffff817cf1c0-ffffffff817cf225: free_list (STB_LOCAL)
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
In drivers/pci/setup-bus.c (ffffffff818f2ed2)
Location: drivers/pci/setup-bus.c:42
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff819362f2)
Location: drivers/pci/setup-bus.c:42
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8197f163)
Location: drivers/pci/setup-bus.c:42
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f1f30)
Location: drivers/pci/setup-bus.c:41
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffff8000106f1f30-ffff8000106f1fa4: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088c960)
Location: drivers/pci/setup-bus.c:41
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
c088c960-c088c9bc: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c00000000086fbf0)
Location: drivers/pci/setup-bus.c:41
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
c00000000086fbf0-c00000000086fcac: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c561c)
Location: drivers/pci/setup-bus.c:41
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffe0004c561c-ffffffe0004c5678: free_list (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81580b90)
Location: drivers/pci/setup-bus.c:41
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff81580b90-ffffffff81580bed: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8156f970)
Location: drivers/pci/setup-bus.c:41
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8156f970-ffffffff8156f9cd: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81580a60)
Location: drivers/pci/setup-bus.c:41
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff81580a60-ffffffff81580abd: free_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8159af10)
Location: drivers/pci/setup-bus.c:41
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8159af10-ffffffff8159af6d: free_list (STB_LOCAL)
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
