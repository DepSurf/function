# Function: <code>cec_notifier_release</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cec_notifier_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff81808b60)
Location: drivers/media/cec/cec-notifier.c:63
Inline: False
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_put
```
**Symbols:**

```
ffffffff81808b60-ffffffff81808ba9: cec_notifier_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cec_notifier_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff8184a490)
Location: drivers/media/cec/cec-notifier.c:74
Inline: False
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_put
```
**Symbols:**

```
ffffffff8184a490-ffffffff8184a4d7: cec_notifier_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_notifier_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff8187bc80)
Location: drivers/media/cec/cec-notifier.c:74
Inline: False
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_put
```
**Symbols:**

```
ffffffff8187bc80-ffffffff8187bcc7: cec_notifier_release (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/media/cec/cec-notifier.c (ffff800010ac35d8)
Location: drivers/media/cec/cec-notifier.c:74
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_put
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
In drivers/media/cec/cec-notifier.c (c0ba50f4)
Location: drivers/media/cec/cec-notifier.c:74
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_put
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
In drivers/media/cec/cec-notifier.c (c000000000ba5f54)
Location: drivers/media/cec/cec-notifier.c:74
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_put
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
In drivers/media/cec/cec-notifier.c (ffffffe0006c41d4)
Location: drivers/media/cec/cec-notifier.c:74
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_put
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
void cec_notifier_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff818241f0)
Location: drivers/media/cec/cec-notifier.c:74
Inline: False
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_put
```
**Symbols:**

```
ffffffff818241f0-ffffffff81824237: cec_notifier_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_notifier_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff817eb890)
Location: drivers/media/cec/cec-notifier.c:74
Inline: False
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_put
```
**Symbols:**

```
ffffffff817eb890-ffffffff817eb8d7: cec_notifier_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_notifier_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff81871130)
Location: drivers/media/cec/cec-notifier.c:74
Inline: False
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_put
```
**Symbols:**

```
ffffffff81871130-ffffffff81871177: cec_notifier_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_notifier_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-notifier.c (ffffffff8188b0f0)
Location: drivers/media/cec/cec-notifier.c:74
Inline: False
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_put
```
**Symbols:**

```
ffffffff8188b0f0-ffffffff8188b137: cec_notifier_release (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
