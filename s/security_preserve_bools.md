# Function: <code>security_preserve_bools</code>

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
In security/selinux/ss/services.c (ffffffff8135946c)
Location: security/selinux/ss/services.c:2697
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff8138f3ee)
Location: security/selinux/ss/services.c:2691
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff813a600e)
Location: security/selinux/ss/services.c:2691
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff813bcb20)
Location: security/selinux/ss/services.c:2807
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff813e2c96)
Location: security/selinux/ss/services.c:2817
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff814124fc)
Location: security/selinux/ss/services.c:2941
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff8142e950)
Location: security/selinux/ss/services.c:2907
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff8145c3cc)
Location: security/selinux/ss/services.c:2920
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff8147617c)
Location: security/selinux/ss/services.c:2927
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_preserve_bools(struct selinux_state *state, struct policydb *policydb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ca100)
Location: security/selinux/ss/services.c:2970
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff814ca100-ffffffff814ca21a: security_preserve_bools (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_preserve_bools(struct selinux_policy *oldpolicy, struct selinux_policy *newpolicy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e9d40)
Location: security/selinux/ss/services.c:3087
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
```
**Symbols:**

```
ffffffff814e9d40-ffffffff814e9e3b: security_preserve_bools (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff814f0a5c)
Location: security/selinux/ss/services.c:3165
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff8154b016)
Location: security/selinux/ss/services.c:3172
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff815e3d6d)
Location: security/selinux/ss/services.c:3174
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff81693022)
Location: security/selinux/ss/services.c:3167
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff816cb550)
Location: security/selinux/ss/services.c:3114
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff817081ee)
Location: security/selinux/ss/services.c:3123
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffff800010565c54)
Location: security/selinux/ss/services.c:2927
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (c071a3f8)
Location: security/selinux/ss/services.c:2927
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (c0000000006c8430)
Location: security/selinux/ss/services.c:2927
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffe0003bbfd4)
Location: security/selinux/ss/services.c:2927
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff8146e75c)
Location: security/selinux/ss/services.c:2927
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff8145f18c)
Location: security/selinux/ss/services.c:2927
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff8146a7fc)
Location: security/selinux/ss/services.c:2927
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
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
In security/selinux/ss/services.c (ffffffff81481f9c)
Location: security/selinux/ss/services.c:2927
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_policy *oldpolicy</code>
</li>
<li>
<b>Param added. </b>
<code>struct selinux_policy *newpolicy</code>
</li>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param removed. </b>
<code>struct policydb *policydb</code>
</li>
</ul>
</details>
</li>
</ul>
