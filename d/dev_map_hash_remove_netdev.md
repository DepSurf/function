# Function: <code>dev_map_hash_remove_netdev</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ff209)
Location: kernel/bpf/devmap.c:741
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_map_hash_remove_netdev(struct bpf_dtab *dtab, struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81226590)
Location: kernel/bpf/devmap.c:772
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
**Symbols:**

```
ffffffff81226590-ffffffff81226675: dev_map_hash_remove_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_map_hash_remove_netdev(struct bpf_dtab *dtab, struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8122d180)
Location: kernel/bpf/devmap.c:766
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
**Symbols:**

```
ffffffff8122d180-ffffffff8122d265: dev_map_hash_remove_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812325e6)
Location: kernel/bpf/devmap.c:771
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8126b972)
Location: kernel/bpf/devmap.c:1047
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812ba819)
Location: kernel/bpf/devmap.c:1036
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
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
In kernel/bpf/devmap.c (ffffffff8131dce5)
Location: kernel/bpf/devmap.c:1036
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
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
In kernel/bpf/devmap.c (ffffffff8134da23)
Location: kernel/bpf/devmap.c:1063
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
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
In kernel/bpf/devmap.c (ffffffff81374f43)
Location: kernel/bpf/devmap.c:1071
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffff8000102871dc)
Location: kernel/bpf/devmap.c:741
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c04b7308)
Location: kernel/bpf/devmap.c:741
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c0000000003315e0)
Location: kernel/bpf/devmap.c:741
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffe0001bb4d6)
Location: kernel/bpf/devmap.c:741
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
</details>
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
In kernel/bpf/devmap.c (ffffffff811f7829)
Location: kernel/bpf/devmap.c:741
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
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
In kernel/bpf/devmap.c (ffffffff811ea579)
Location: kernel/bpf/devmap.c:741
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
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
In kernel/bpf/devmap.c (ffffffff811f55f9)
Location: kernel/bpf/devmap.c:741
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
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
In kernel/bpf/devmap.c (ffffffff81203b53)
Location: kernel/bpf/devmap.c:741
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
