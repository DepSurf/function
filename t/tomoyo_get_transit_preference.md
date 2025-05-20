# Function: <code>tomoyo_get_transit_preference</code>

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
In security/tomoyo/condition.c (ffffffff8136bb76)
Location: security/tomoyo/condition.c:439
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff813a1d86)
Location: security/tomoyo/condition.c:439
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff813b8906)
Location: security/tomoyo/condition.c:439
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff813cf1c6)
Location: security/tomoyo/condition.c:439
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff813f5676)
Location: security/tomoyo/condition.c:440
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff814265fc)
Location: security/tomoyo/condition.c:440
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff81442cec)
Location: security/tomoyo/condition.c:440
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff8147092c)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff8148a6cc)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *tomoyo_get_transit_preference(struct tomoyo_acl_param *param, struct tomoyo_condition *e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff814e17c0)
Location: security/tomoyo/condition.c:454
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
**Symbols:**

```
ffffffff814e17c0-ffffffff814e1953: tomoyo_get_transit_preference (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *tomoyo_get_transit_preference(struct tomoyo_acl_param *param, struct tomoyo_condition *e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff814feb60)
Location: security/tomoyo/condition.c:454
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
**Symbols:**

```
ffffffff814feb60-ffffffff814fecf3: tomoyo_get_transit_preference (STB_LOCAL)
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
In security/tomoyo/condition.c (0)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (0)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff815fdecc)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff816aed4c)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff816e776c)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff8172447c)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffff80001057dd7c)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (c07300e4)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (c0000000006e9ab4)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffe0003ceed8)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff81482cac)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff814736cc)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff8147ed4c)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff8149687c)
Location: security/tomoyo/condition.c:454
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
