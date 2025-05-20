# Function: <code>propagate_exception</code>

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
Location: security/device_cgroup.c:542
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
Location: security/device_cgroup.c:542
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
Location: security/device_cgroup.c:542
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
In security/device_cgroup.c (ffffffff813f5744)
Location: security/device_cgroup.c:542
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
In security/device_cgroup.c (ffffffff8141da04)
Location: security/device_cgroup.c:534
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
In security/device_cgroup.c (ffffffff8144fc95)
Location: security/device_cgroup.c:534
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
In security/device_cgroup.c (ffffffff8146cc75)
Location: security/device_cgroup.c:534
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
In security/device_cgroup.c (ffffffff8149a36a)
Location: security/device_cgroup.c:533
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
In security/device_cgroup.c (ffffffff814b456a)
Location: security/device_cgroup.c:533
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
int propagate_exception(struct dev_cgroup *devcg_root, struct dev_exception_item *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81513630)
Location: security/device_cgroup.c:536
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_update_access
```
**Symbols:**

```
ffffffff81513630-ffffffff815136bc: propagate_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int propagate_exception(struct dev_cgroup *devcg_root, struct dev_exception_item *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81530780)
Location: security/device_cgroup.c:536
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_update_access
```
**Symbols:**

```
ffffffff81530780-ffffffff8153080f: propagate_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int propagate_exception(struct dev_cgroup *devcg_root, struct dev_exception_item *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff815368c0)
Location: security/device_cgroup.c:536
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_update_access
```
**Symbols:**

```
ffffffff815368c0-ffffffff81536a0f: propagate_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int propagate_exception(struct dev_cgroup *devcg_root, struct dev_exception_item *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81594ff0)
Location: security/device_cgroup.c:536
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_update_access
```
**Symbols:**

```
ffffffff81594ff0-ffffffff8159513f: propagate_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int propagate_exception(struct dev_cgroup *devcg_root, struct dev_exception_item *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff816371c0)
Location: security/device_cgroup.c:537
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_update_access
```
**Symbols:**

```
ffffffff816371c0-ffffffff8163732e: propagate_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int propagate_exception(struct dev_cgroup *devcg_root, struct dev_exception_item *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff816ee430)
Location: security/device_cgroup.c:548
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_update_access
```
**Symbols:**

```
ffffffff816ee430-ffffffff816ee59e: propagate_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int propagate_exception(struct dev_cgroup *devcg_root, struct dev_exception_item *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81728920)
Location: security/device_cgroup.c:548
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_update_access
```
**Symbols:**

```
ffffffff81728920-ffffffff81728a8e: propagate_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int propagate_exception(struct dev_cgroup *devcg_root, struct dev_exception_item *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81769c80)
Location: security/device_cgroup.c:548
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_update_access
```
**Symbols:**

```
ffffffff81769c80-ffffffff81769dee: propagate_exception (STB_LOCAL)
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
In security/device_cgroup.c (ffff8000105ac4e8)
Location: security/device_cgroup.c:533
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
In security/device_cgroup.c (c075bf60)
Location: security/device_cgroup.c:533
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
In security/device_cgroup.c (c00000000072a904)
Location: security/device_cgroup.c:533
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
In security/device_cgroup.c (ffffffe0003f4c1e)
Location: security/device_cgroup.c:533
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
In security/device_cgroup.c (ffffffff814acb4a)
Location: security/device_cgroup.c:533
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
In security/device_cgroup.c (ffffffff8149d56a)
Location: security/device_cgroup.c:533
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
In security/device_cgroup.c (ffffffff814a8bea)
Location: security/device_cgroup.c:533
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
In security/device_cgroup.c (ffffffff814c15b6)
Location: security/device_cgroup.c:533
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
