# Function: <code>dax_entry_waitqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81287756)
Location: fs/dax.c:65
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_mapping_entry_waiter
  - fs/dax.c:get_unlocked_mapping_entry
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
In fs/dax.c (ffffffff8129b32c)
Location: fs/dax.c:133
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_mapping_entry_waiter
  - fs/dax.c:get_unlocked_mapping_entry
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
In fs/dax.c (ffffffff812a9ef3)
Location: fs/dax.c:124
Inline: True
Inline callers:
  - fs/dax.c:get_unlocked_mapping_entry
  - fs/dax.c:dax_wake_mapping_entry_waiter
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
In fs/dax.c (ffffffff812cd4a3)
Location: fs/dax.c:127
Inline: True
Inline callers:
  - fs/dax.c:get_unlocked_mapping_entry
  - fs/dax.c:dax_wake_mapping_entry_waiter
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
In fs/dax.c (ffffffff812f7805)
Location: fs/dax.c:127
Inline: True
Inline callers:
  - fs/dax.c:__get_unlocked_mapping_entry
  - fs/dax.c:dax_wake_mapping_entry_waiter
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
In fs/dax.c (ffffffff8130cbe2)
Location: fs/dax.c:146
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff813341ae)
Location: fs/dax.c:147
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff81347d6e)
Location: fs/dax.c:147
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138d2fe)
Location: fs/dax.c:147
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139ea8e)
Location: fs/dax.c:147
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff813a5b7e)
Location: fs/dax.c:157
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff813f55ee)
Location: fs/dax.c:157
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff81467718)
Location: fs/dax.c:157
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff814f7a28)
Location: fs/dax.c:157
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff8152e878)
Location: fs/dax.c:157
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff81563758)
Location: fs/dax.c:143
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffff800010407fc0)
Location: fs/dax.c:147
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000513e08)
Location: fs/dax.c:147
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffe0002b2b22)
Location: fs/dax.c:147
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff8134034e)
Location: fs/dax.c:147
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff81330fce)
Location: fs/dax.c:147
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff8133de1e)
Location: fs/dax.c:147
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff8134ffce)
Location: fs/dax.c:147
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
</details>
</li>
</ul>

## Differences
