# Function: <code>tomoyo_inet_entry</code>

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
In security/tomoyo/network.c (ffffffff81371dd4)
Location: security/tomoyo/network.c:466
Inline: True
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
In security/tomoyo/network.c (ffffffff813a8204)
Location: security/tomoyo/network.c:466
Inline: True
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
In security/tomoyo/network.c (ffffffff813bed94)
Location: security/tomoyo/network.c:466
Inline: True
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
In security/tomoyo/network.c (ffffffff813d56c5)
Location: security/tomoyo/network.c:466
Inline: True
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
In security/tomoyo/network.c (ffffffff813fbbd5)
Location: security/tomoyo/network.c:467
Inline: True
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
In security/tomoyo/network.c (ffffffff8142cae0)
Location: security/tomoyo/network.c:467
Inline: True
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
In security/tomoyo/network.c (ffffffff81449430)
Location: security/tomoyo/network.c:467
Inline: True
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
In security/tomoyo/network.c (ffffffff814770cd)
Location: security/tomoyo/network.c:467
Inline: True
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
In security/tomoyo/network.c (ffffffff81490e6d)
Location: security/tomoyo/network.c:467
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_inet_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff814e8160)
Location: security/tomoyo/network.c:467
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
**Symbols:**

```
ffffffff814e8160-ffffffff814e825a: tomoyo_inet_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_inet_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff815054e0)
Location: security/tomoyo/network.c:467
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
**Symbols:**

```
ffffffff815054e0-ffffffff815055da: tomoyo_inet_entry (STB_LOCAL)
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
In security/tomoyo/network.c (ffffffff8150c0f9)
Location: security/tomoyo/network.c:467
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_check_inet_address
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
In security/tomoyo/network.c (ffffffff815698cd)
Location: security/tomoyo/network.c:467
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_check_inet_address
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
In security/tomoyo/network.c (ffffffff8160570d)
Location: security/tomoyo/network.c:467
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_check_inet_address
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
In security/tomoyo/network.c (ffffffff816b6aed)
Location: security/tomoyo/network.c:467
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_check_inet_address
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
In security/tomoyo/network.c (ffffffff816ef49c)
Location: security/tomoyo/network.c:467
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_check_inet_address
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
In security/tomoyo/network.c (ffffffff8172c26c)
Location: security/tomoyo/network.c:467
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_check_inet_address
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
In security/tomoyo/network.c (ffff8000105852f4)
Location: security/tomoyo/network.c:467
Inline: True
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
In security/tomoyo/network.c (c0736cb4)
Location: security/tomoyo/network.c:467
Inline: True
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
In security/tomoyo/network.c (c0000000006f4938)
Location: security/tomoyo/network.c:467
Inline: True
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
In security/tomoyo/network.c (ffffffe0003d4fcc)
Location: security/tomoyo/network.c:467
Inline: True
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
In security/tomoyo/network.c (ffffffff8148944d)
Location: security/tomoyo/network.c:467
Inline: True
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
In security/tomoyo/network.c (ffffffff81479e6d)
Location: security/tomoyo/network.c:467
Inline: True
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
In security/tomoyo/network.c (ffffffff814854ed)
Location: security/tomoyo/network.c:467
Inline: True
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
In security/tomoyo/network.c (ffffffff8149d02d)
Location: security/tomoyo/network.c:467
Inline: True
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
