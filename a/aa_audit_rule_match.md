# Function: <code>aa_audit_rule_match</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_audit_rule_match(u32 sid, u32 field, u32 op, void *vrule, struct audit_context *actx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81434370)
Location: security/apparmor/audit.c:228
Inline: False
```
**Symbols:**

```
ffffffff81434370-ffffffff814343d5: aa_audit_rule_match (STB_GLOBAL)
```
</details>
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
int aa_audit_rule_match(u32 sid, u32 field, u32 op, void *vrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff814f0a20)
Location: security/apparmor/audit.c:225
Inline: False
```
**Symbols:**

```
ffffffff814f0a20-ffffffff814f0a8d: aa_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_audit_rule_match(u32 sid, u32 field, u32 op, void *vrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8150dca0)
Location: security/apparmor/audit.c:223
Inline: False
```
**Symbols:**

```
ffffffff8150dca0-ffffffff8150dd0d: aa_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_audit_rule_match(u32 sid, u32 field, u32 op, void *vrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff815146b0)
Location: security/apparmor/audit.c:223
Inline: False
```
**Symbols:**

```
ffffffff815146b0-ffffffff8151471a: aa_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_audit_rule_match(u32 sid, u32 field, u32 op, void *vrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81572570)
Location: security/apparmor/audit.c:223
Inline: False
```
**Symbols:**

```
ffffffff81572570-ffffffff815725da: aa_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_audit_rule_match(u32 sid, u32 field, u32 op, void *vrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff8160f520)
Location: security/apparmor/audit.c:266
Inline: False
```
**Symbols:**

```
ffffffff8160f520-ffffffff8160f59b: aa_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_audit_rule_match(u32 sid, u32 field, u32 op, void *vrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff816c1900)
Location: security/apparmor/audit.c:267
Inline: False
```
**Symbols:**

```
ffffffff816c1900-ffffffff816c197b: aa_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_audit_rule_match(u32 sid, u32 field, u32 op, void *vrule);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff816fa520)
Location: security/apparmor/audit.c:269
Inline: False
```
**Symbols:**

```
ffffffff816fa520-ffffffff816fa59b: aa_audit_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_audit_rule_match(struct lsmblob *blob, u32 field, u32 op, void *vrule, int lsmid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/audit.c (ffffffff81737190)
Location: security/apparmor/audit.c:274
Inline: False
```
**Symbols:**

```
ffffffff81737190-ffffffff817371a1: aa_audit_rule_match (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmblob *blob</code>
</li>
<li>
<b>Param added. </b>
<code>int lsmid</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 sid</code>
</li>
</ul>
</details>
</li>
</ul>
