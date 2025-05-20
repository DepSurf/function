# Function: <code>revalidate_active_exceptions</code>

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
In security/device_cgroup.c (ffffffff81395e09)
Location: security/device_cgroup.c:523
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff813d1b62)
Location: security/device_cgroup.c:523
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff813e927f)
Location: security/device_cgroup.c:523
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff813f5788)
Location: security/device_cgroup.c:523
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff8141da48)
Location: security/device_cgroup.c:515
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff8144fcdc)
Location: security/device_cgroup.c:515
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff8146ccbc)
Location: security/device_cgroup.c:515
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff8149a3b8)
Location: security/device_cgroup.c:514
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff814b45b8)
Location: security/device_cgroup.c:514
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void revalidate_active_exceptions(struct dev_cgroup *devcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81513570)
Location: security/device_cgroup.c:517
Inline: False
Direct callers:
  - security/device_cgroup.c:propagate_exception
```
**Symbols:**

```
ffffffff81513570-ffffffff8151362b: revalidate_active_exceptions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void revalidate_active_exceptions(struct dev_cgroup *devcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff815306c0)
Location: security/device_cgroup.c:517
Inline: False
Direct callers:
  - security/device_cgroup.c:propagate_exception
```
**Symbols:**

```
ffffffff815306c0-ffffffff8153077b: revalidate_active_exceptions (STB_LOCAL)
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
In security/device_cgroup.c (ffffffff81536934)
Location: security/device_cgroup.c:517
Inline: True
Inline callers:
  - security/device_cgroup.c:propagate_exception
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
In security/device_cgroup.c (ffffffff81595064)
Location: security/device_cgroup.c:517
Inline: True
Inline callers:
  - security/device_cgroup.c:propagate_exception
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
In security/device_cgroup.c (ffffffff8163723b)
Location: security/device_cgroup.c:518
Inline: True
Inline callers:
  - security/device_cgroup.c:propagate_exception
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
In security/device_cgroup.c (ffffffff816ee4ab)
Location: security/device_cgroup.c:529
Inline: True
Inline callers:
  - security/device_cgroup.c:propagate_exception
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
In security/device_cgroup.c (ffffffff8172899b)
Location: security/device_cgroup.c:529
Inline: True
Inline callers:
  - security/device_cgroup.c:propagate_exception
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
In security/device_cgroup.c (ffffffff81769cfb)
Location: security/device_cgroup.c:529
Inline: True
Inline callers:
  - security/device_cgroup.c:propagate_exception
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
In security/device_cgroup.c (ffff8000105ac534)
Location: security/device_cgroup.c:514
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (c075bfac)
Location: security/device_cgroup.c:514
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (c00000000072a958)
Location: security/device_cgroup.c:514
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffe0003f4c58)
Location: security/device_cgroup.c:514
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff814acb98)
Location: security/device_cgroup.c:514
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff8149d5b8)
Location: security/device_cgroup.c:514
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff814a8c38)
Location: security/device_cgroup.c:514
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
In security/device_cgroup.c (ffffffff814c1612)
Location: security/device_cgroup.c:514
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
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
