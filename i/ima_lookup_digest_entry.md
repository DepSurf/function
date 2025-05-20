# Function: <code>ima_lookup_digest_entry</code>

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
In security/integrity/ima/ima_queue.c (ffffffff8139714b)
Location: security/integrity/ima/ima_queue.c:47
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff813d3193)
Location: security/integrity/ima/ima_queue.c:47
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff813ea9e4)
Location: security/integrity/ima/ima_queue.c:52
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff813f6d1f)
Location: security/integrity/ima/ima_queue.c:52
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff8141ee3f)
Location: security/integrity/ima/ima_queue.c:52
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff814510c3)
Location: security/integrity/ima/ima_queue.c:52
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff8146e0a5)
Location: security/integrity/ima/ima_queue.c:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff8149b775)
Location: security/integrity/ima/ima_queue.c:50
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff814b59b5)
Location: security/integrity/ima/ima_queue.c:50
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ima_queue_entry *ima_lookup_digest_entry(u8 *digest_value, int pcr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff81514e20)
Location: security/integrity/ima/ima_queue.c:48
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81514e20-ffffffff81514eba: ima_lookup_digest_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ima_queue_entry *ima_lookup_digest_entry(u8 *digest_value, int pcr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff81531e90)
Location: security/integrity/ima/ima_queue.c:48
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81531e90-ffffffff81531f2f: ima_lookup_digest_entry (STB_LOCAL)
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
In security/integrity/ima/ima_queue.c (ffffffff8153a4b6)
Location: security/integrity/ima/ima_queue.c:48
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff81598e37)
Location: security/integrity/ima/ima_queue.c:48
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff8163d93e)
Location: security/integrity/ima/ima_queue.c:48
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff816f54ac)
Location: security/integrity/ima/ima_queue.c:48
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff8172f59e)
Location: security/integrity/ima/ima_queue.c:48
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff8176ff2e)
Location: security/integrity/ima/ima_queue.c:48
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffff8000105ade80)
Location: security/integrity/ima/ima_queue.c:50
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (c075d558)
Location: security/integrity/ima/ima_queue.c:50
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (c00000000072ca64)
Location: security/integrity/ima/ima_queue.c:50
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffe0003f618c)
Location: security/integrity/ima/ima_queue.c:50
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff814adf95)
Location: security/integrity/ima/ima_queue.c:50
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff8149e9b5)
Location: security/integrity/ima/ima_queue.c:50
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff814aa035)
Location: security/integrity/ima/ima_queue.c:50
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff814c2a8b)
Location: security/integrity/ima/ima_queue.c:50
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
