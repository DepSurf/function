# Function: <code>auditd_reset</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void auditd_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811329c0)
Location: kernel/audit.c:451
Inline: False
Direct callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff811329c0-ffffffff81132a26: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81134130)
Location: kernel/audit.c:587
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81134130-ffffffff811341c2: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81140ef0)
Location: kernel/audit.c:587
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81140ef0-ffffffff81140f82: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8114f870)
Location: kernel/audit.c:630
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff8114f870-ffffffff8114f902: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115c550)
Location: kernel/audit.c:626
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff8115c550-ffffffff8115c5e2: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81168c20)
Location: kernel/audit.c:613
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81168c20-ffffffff81168cad: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81174ac0)
Location: kernel/audit.c:613
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81174ac0-ffffffff81174b4d: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81186b30)
Location: kernel/audit.c:615
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81186b30-ffffffff81186bbd: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81183e50)
Location: kernel/audit.c:620
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81183e50-ffffffff81183edd: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81184d80)
Location: kernel/audit.c:620
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81184d80-ffffffff81184e0d: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811ad160)
Location: kernel/audit.c:642
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff811ad160-ffffffff811ad1f2: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811dee20)
Location: kernel/audit.c:643
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff811dee20-ffffffff811deec6: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81224ae0)
Location: kernel/audit.c:641
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81224ae0-ffffffff81224b86: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123b0b0)
Location: kernel/audit.c:641
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff8123b0b0-ffffffff8123b156: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81254f70)
Location: kernel/audit.c:652
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81254f70-ffffffff81255016: auditd_reset (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101e96d8)
Location: kernel/audit.c:613
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffff8000101e96d8-ffff8000101e97f8: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c04295b8)
Location: kernel/audit.c:613
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
c04295b8-c0429650: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025a530)
Location: kernel/audit.c:613
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
c00000000025a530-c00000000025a658: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015e43c)
Location: kernel/audit.c:613
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffe00015e43c-ffffffe00015e4f4: auditd_reset (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116d0e0)
Location: kernel/audit.c:613
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff8116d0e0-ffffffff8116d16d: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81160280)
Location: kernel/audit.c:613
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81160280-ffffffff8116030d: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116aeb0)
Location: kernel/audit.c:613
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff8116aeb0-ffffffff8116af3d: auditd_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void auditd_reset(const struct auditd_connection *ac);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811786c0)
Location: kernel/audit.c:613
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff811786c0-ffffffff8117874d: auditd_reset (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct auditd_connection *ac</code>
</li>
</ul>
</details>
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
