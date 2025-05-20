# Function: <code>ima_alloc_key_entry</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ima_key_entry *ima_alloc_key_entry(struct key *keyring, const void *payload, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff8151cb60)
Location: security/integrity/ima/ima_queue_keys.c:66
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
```
**Symbols:**

```
ffffffff8151cb60-ffffffff8151cc11: ima_alloc_key_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ima_key_entry *ima_alloc_key_entry(struct key *keyring, const void *payload, size_t payload_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff815399a0)
Location: security/integrity/ima/ima_queue_keys.c:66
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
```
**Symbols:**

```
ffffffff815399a0-ffffffff81539abf: ima_alloc_key_entry (STB_LOCAL)
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
In security/integrity/ima/ima_queue_keys.c (ffffffff815420f5)
Location: security/integrity/ima/ima_queue_keys.c:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
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
In security/integrity/ima/ima_queue_keys.c (ffffffff815a2065)
Location: security/integrity/ima/ima_queue_keys.c:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
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
In security/integrity/ima/ima_queue_keys.c (ffffffff816484bd)
Location: security/integrity/ima/ima_queue_keys.c:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
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
In security/integrity/ima/ima_queue_keys.c (ffffffff817011bd)
Location: security/integrity/ima/ima_queue_keys.c:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
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
In security/integrity/ima/ima_queue_keys.c (ffffffff8173b25d)
Location: security/integrity/ima/ima_queue_keys.c:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
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
In security/integrity/ima/ima_queue_keys.c (ffffffff8177bded)
Location: security/integrity/ima/ima_queue_keys.c:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
