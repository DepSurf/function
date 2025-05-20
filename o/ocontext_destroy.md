# Function: <code>ocontext_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ocontext_destroy(struct ocontext *c, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81351cb0)
Location: security/selinux/ss/policydb.c:776
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81351cb0-ffffffff81351de4: ocontext_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ocontext_destroy(struct ocontext *c, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81387cb0)
Location: security/selinux/ss/policydb.c:776
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff81387cb0-ffffffff81387de4: ocontext_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ocontext_destroy(struct ocontext *c, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8139e760)
Location: security/selinux/ss/policydb.c:776
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff8139e760-ffffffff8139e894: ocontext_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b6cf0)
Location: security/selinux/ss/policydb.c:780
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff813b4050-ffffffff813b416e: ocontext_destroy.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813dce52)
Location: security/selinux/ss/policydb.c:780
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff813da1a0-ffffffff813da2be: ocontext_destroy.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8140e3a8)
Location: security/selinux/ss/policydb.c:780
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff8140a5b0-ffffffff8140a6ce: ocontext_destroy.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8142a4f7)
Location: security/selinux/ss/policydb.c:783
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff814269e0-ffffffff81426afe: ocontext_destroy.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8145731e)
Location: security/selinux/ss/policydb.c:744
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff81454160-ffffffff81454293: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814710be)
Location: security/selinux/ss/policydb.c:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff8146df00-ffffffff8146e033: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814c654e)
Location: security/selinux/ss/policydb.c:367
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff814c2580-ffffffff814c26b3: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814e458e)
Location: security/selinux/ss/policydb.c:367
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff814e00b0-ffffffff814e01e3: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff814eaf4e)
Location: security/selinux/ss/policydb.c:367
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff814e69a0-ffffffff814e6acd: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8154498e)
Location: security/selinux/ss/policydb.c:367
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff81540230-ffffffff8154035d: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff815dd345)
Location: security/selinux/ss/policydb.c:362
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff815d83a0-ffffffff815d84c4: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8168bdcb)
Location: security/selinux/ss/policydb.c:362
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff81686dd0-ffffffff81686ef4: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c414b)
Location: security/selinux/ss/policydb.c:362
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff816bfd50-ffffffff816bfe76: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81700c73)
Location: security/selinux/ss/policydb.c:362
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff816fc650-ffffffff816fc776: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffff80001056083c)
Location: security/selinux/ss/policydb.c:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffff80001055d3c8-ffff80001055d488: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (c0715104)
Location: security/selinux/ss/policydb.c:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
c071190c-c07119dc: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006c1628)
Location: security/selinux/ss/policydb.c:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
c0000000006bcfe0-c0000000006bd124: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b7d84)
Location: security/selinux/ss/policydb.c:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffe0003b5da4-ffffffe0003b5e7a: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8146969e)
Location: security/selinux/ss/policydb.c:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff814664e0-ffffffff81466613: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8145a0ce)
Location: security/selinux/ss/policydb.c:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff81456f10-ffffffff81457043: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8146573e)
Location: security/selinux/ss/policydb.c:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff81462580-ffffffff814626b3: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8147cf1e)
Location: security/selinux/ss/policydb.c:355
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
Direct callers:
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
```
**Symbols:**

```
ffffffff81479d80-ffffffff81479eb3: ocontext_destroy.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
