# Function: <code>audit_log_proctitle</code>

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
In kernel/auditsc.c (ffffffff81125f00)
Location: kernel/auditsc.c:1283
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff8112e3ea)
Location: kernel/auditsc.c:1282
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff8113812a)
Location: kernel/auditsc.c:1287
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff81139802)
Location: kernel/auditsc.c:1294
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff811464f2)
Location: kernel/auditsc.c:1294
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff81155004)
Location: kernel/auditsc.c:1305
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff81161e80)
Location: kernel/auditsc.c:1261
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff8116f8a6)
Location: kernel/auditsc.c:1400
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff8117b726)
Location: kernel/auditsc.c:1400
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_log_proctitle();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d340)
Location: kernel/auditsc.c:1384
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8118d340-ffffffff8118d486: audit_log_proctitle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_log_proctitle();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118a510)
Location: kernel/auditsc.c:1405
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8118a510-ffffffff8118a640: audit_log_proctitle (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8118db4c)
Location: kernel/auditsc.c:1404
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff811b687c)
Location: kernel/auditsc.c:1413
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff811e9148)
Location: kernel/auditsc.c:1598
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff8122f1e8)
Location: kernel/auditsc.c:1576
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff8124611e)
Location: kernel/auditsc.c:1573
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_log_proctitle();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8125c4a0)
Location: kernel/auditsc.c:1568
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_log_exit
```
**Symbols:**

```
ffffffff8125c4a0-ffffffff8125c5fe: audit_log_proctitle (STB_LOCAL)
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
In kernel/auditsc.c (ffff8000101f1384)
Location: kernel/auditsc.c:1400
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (c0430934)
Location: kernel/auditsc.c:1400
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (c000000000264c14)
Location: kernel/auditsc.c:1400
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffe000164e20)
Location: kernel/auditsc.c:1400
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff81173d46)
Location: kernel/auditsc.c:1400
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff81166ee6)
Location: kernel/auditsc.c:1400
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff81171b16)
Location: kernel/auditsc.c:1400
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
In kernel/auditsc.c (ffffffff8117f326)
Location: kernel/auditsc.c:1400
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_log_exit
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
