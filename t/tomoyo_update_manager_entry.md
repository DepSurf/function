# Function: <code>tomoyo_update_manager_entry</code>

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
In security/tomoyo/common.c (ffffffff81367d6c)
Location: security/tomoyo/common.c:842
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (ffffffff8139de57)
Location: security/tomoyo/common.c:842
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (ffffffff813b4a37)
Location: security/tomoyo/common.c:842
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (ffffffff813cb3d7)
Location: security/tomoyo/common.c:842
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (ffffffff813f1867)
Location: security/tomoyo/common.c:843
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (ffffffff81422695)
Location: security/tomoyo/common.c:843
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (ffffffff8143ecf5)
Location: security/tomoyo/common.c:843
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (ffffffff8146c94c)
Location: security/tomoyo/common.c:861
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (ffffffff8148672c)
Location: security/tomoyo/common.c:861
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_update_manager_entry(const char *manager, const bool is_delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814dd570)
Location: security/tomoyo/common.c:861
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
```
**Symbols:**

```
ffffffff814dd570-ffffffff814dd65e: tomoyo_update_manager_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_update_manager_entry(const char *manager, const bool is_delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814fa990)
Location: security/tomoyo/common.c:861
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_manager
```
**Symbols:**

```
ffffffff814fa990-ffffffff814faa7e: tomoyo_update_manager_entry (STB_LOCAL)
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
In security/tomoyo/common.c (ffffffff81501609)
Location: security/tomoyo/common.c:861
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (ffffffff8155cc05)
Location: security/tomoyo/common.c:861
Inline: True
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
In security/tomoyo/common.c (ffffffff815f7d29)
Location: security/tomoyo/common.c:852
Inline: True
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
In security/tomoyo/common.c (ffffffff816a8959)
Location: security/tomoyo/common.c:852
Inline: True
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
In security/tomoyo/common.c (ffffffff816e1399)
Location: security/tomoyo/common.c:852
Inline: True
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
In security/tomoyo/common.c (ffffffff8171e019)
Location: security/tomoyo/common.c:853
Inline: True
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
In security/tomoyo/common.c (ffff80001057b840)
Location: security/tomoyo/common.c:861
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (c072bca4)
Location: security/tomoyo/common.c:861
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (c0000000006e2a40)
Location: security/tomoyo/common.c:861
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (ffffffe0003cb024)
Location: security/tomoyo/common.c:861
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (ffffffff8147ed0c)
Location: security/tomoyo/common.c:861
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (ffffffff8146f72c)
Location: security/tomoyo/common.c:861
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (ffffffff8147adac)
Location: security/tomoyo/common.c:861
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
In security/tomoyo/common.c (ffffffff8149299c)
Location: security/tomoyo/common.c:861
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_manager
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
