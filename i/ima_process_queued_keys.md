# Function: <code>ima_process_queued_keys</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ima_process_queued_keys();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff8151cd13)
Location: security/integrity/ima/ima_queue_keys.c:127
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_keys_handler
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_queue_keys.c:ima_keys_handler
```
**Symbols:**

```
ffffffff8151cc20-ffffffff8151ccf7: ima_process_queued_keys.part.0 (STB_LOCAL)
ffffffff8151ce30-ffffffff8151ce80: ima_process_queued_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ima_process_queued_keys();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff81539bb3)
Location: security/integrity/ima/ima_queue_keys.c:132
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_keys_handler
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_queue_keys.c:ima_keys_handler
```
**Symbols:**

```
ffffffff81539ac0-ffffffff81539b9d: ima_process_queued_keys.part.0 (STB_LOCAL)
ffffffff81539cd0-ffffffff81539d20: ima_process_queued_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ima_process_queued_keys();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff81542280)
Location: security/integrity/ima/ima_queue_keys.c:133
Inline: True
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_queue_keys.c:ima_keys_handler
```
**Symbols:**

```
ffffffff81542280-ffffffff815423ae: ima_process_queued_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ima_process_queued_keys();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff815a2236)
Location: security/integrity/ima/ima_queue_keys.c:133
Inline: True
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_queue_keys.c:ima_keys_handler
```
**Symbols:**

```
ffffffff81cd7453-ffffffff81cd74a4: ima_process_queued_keys.cold (STB_LOCAL)
ffffffff815a2200-ffffffff815a237a: ima_process_queued_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ima_process_queued_keys();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff8164868a)
Location: security/integrity/ima/ima_queue_keys.c:133
Inline: True
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_queue_keys.c:ima_keys_handler
```
**Symbols:**

```
ffffffff81e8a689-ffffffff81e8a6da: ima_process_queued_keys.cold (STB_LOCAL)
ffffffff81648640-ffffffff816487d9: ima_process_queued_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ima_process_queued_keys();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff8170139a)
Location: security/integrity/ima/ima_queue_keys.c:133
Inline: True
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_queue_keys.c:ima_keys_handler
```
**Symbols:**

```
ffffffff820755aa-ffffffff820755fb: ima_process_queued_keys.cold (STB_LOCAL)
ffffffff81701350-ffffffff817014e9: ima_process_queued_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ima_process_queued_keys();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff8173b43a)
Location: security/integrity/ima/ima_queue_keys.c:133
Inline: True
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_queue_keys.c:ima_keys_handler
```
**Symbols:**

```
ffffffff820f510c-ffffffff820f515d: ima_process_queued_keys.cold (STB_LOCAL)
ffffffff8173b3f0-ffffffff8173b589: ima_process_queued_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ima_process_queued_keys();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff8177bffa)
Location: security/integrity/ima/ima_queue_keys.c:133
Inline: True
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
  - security/integrity/ima/ima_queue_keys.c:ima_keys_handler
```
**Symbols:**

```
ffffffff821d22b6-ffffffff821d2307: ima_process_queued_keys.cold (STB_LOCAL)
ffffffff8177bfb0-ffffffff8177c149: ima_process_queued_keys (STB_GLOBAL)
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
