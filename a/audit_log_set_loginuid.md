# Function: <code>audit_log_set_loginuid</code>

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
In kernel/auditsc.c (ffffffff81128e65)
Location: kernel/auditsc.c:1977
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
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
In kernel/auditsc.c (ffffffff81130ff8)
Location: kernel/auditsc.c:1976
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
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
In kernel/auditsc.c (ffffffff8113ad6b)
Location: kernel/auditsc.c:1981
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
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
In kernel/auditsc.c (ffffffff8113c37b)
Location: kernel/auditsc.c:1990
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
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
In kernel/auditsc.c (ffffffff811490fb)
Location: kernel/auditsc.c:2013
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
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
In kernel/auditsc.c (ffffffff81157a9f)
Location: kernel/auditsc.c:2020
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
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
In kernel/auditsc.c (ffffffff81164aa1)
Location: kernel/auditsc.c:2006
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
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
In kernel/audit.c (ffffffff8116b508)
Location: kernel/audit.c:2199
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (ffffffff811773e8)
Location: kernel/audit.c:2201
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_log_set_loginuid(kuid_t koldloginuid, kuid_t kloginuid, unsigned int oldsessionid, unsigned int sessionid, int rc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81189ea0)
Location: kernel/audit.c:2351
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff81189ea0-ffffffff8118a008: audit_log_set_loginuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_log_set_loginuid(kuid_t koldloginuid, kuid_t kloginuid, unsigned int oldsessionid, unsigned int sessionid, int rc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811871a0)
Location: kernel/audit.c:2368
Inline: False
Direct callers:
  - kernel/audit.c:audit_set_loginuid
```
**Symbols:**

```
ffffffff811871a0-ffffffff81187313: audit_log_set_loginuid (STB_LOCAL)
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
In kernel/audit.c (ffffffff8118839b)
Location: kernel/audit.c:2368
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (ffffffff811b08bb)
Location: kernel/audit.c:2407
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (ffffffff811e2a9a)
Location: kernel/audit.c:2453
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (ffffffff8122897a)
Location: kernel/audit.c:2451
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (ffffffff8123ef7a)
Location: kernel/audit.c:2451
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (ffffffff81258deb)
Location: kernel/audit.c:2473
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (ffff8000101ec390)
Location: kernel/audit.c:2201
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (c042bfd0)
Location: kernel/audit.c:2201
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (c00000000025dd74)
Location: kernel/audit.c:2201
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (ffffffe000160aba)
Location: kernel/audit.c:2201
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (ffffffff8116fa08)
Location: kernel/audit.c:2201
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (ffffffff81162ba8)
Location: kernel/audit.c:2201
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (ffffffff8116d7d8)
Location: kernel/audit.c:2201
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
In kernel/audit.c (ffffffff8117afcd)
Location: kernel/audit.c:2201
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
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
