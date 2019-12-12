# Add and Manage Data Filters

On a dashboard, you can add a filter for the data results and display only the data that contain a particular value. You can also create negative filters that exclude data that contain the specified value. Filtering makes it easier for you to focus on specific information in a dashboard. The applied filters show in the query bar. Negative filters show in red.

After you add a filter, you can manage it by applying quick actions on the filter label such as excluding matches, and editing or removing the filter.

* [Add a Filter](add-and-manage-data-filters.md#add-a-filter)
* [Edit a Filter](add-and-manage-data-filters.md#edit-a-filter)
* [Manage a Filter](add-and-manage-data-filters.md#manage-a-filter)

### Add a Filter

**Do these steps:**

1. On a dashboard, click **Add a filter +**. ****The Add filter dialog appears.
2. Click in the **Filter** field and:
   * Add filters from the Fields drop-down list. ![](../.gitbook/assets/addfilter.png)  
   * Type a filter value in the **Filter** field. The Add filter dialog appears—enter values in the **Filter** and **Label** fields. 
3. Click **Edit Query DSL** to build a filter using using Elasticsearch Query DSL. You can create positive and negative operators and filter on whether or not a field is present. The Label field lets you enter a label value that identifies your filter subject. ![](../.gitbook/assets/7405883.png) 
4. Click **Save**. The filter label appears in the Actions bar.
5. \(Optional\) Cick **Actions** to show the **All filters** options as shown in the following example: ![](../.gitbook/assets/actions.png)  
   * **Enable** enables a disabled filter.
   * **Disable** disables the filter without removing it. Diagonal stripes indicate that a filter is disabled.
   * **Pin** pins the filter. Pinned filters persist when you switch contexts. For example, you can pin a filter in one dashboard and it remains in place when you switch to another dashboard. A filter is based on a particular index field—if the indices being searched do not contain the field in a pinned filter, it has no effect.
   * **Unpin** disables a pin filter.
   * **Invert** switches from a positive filter to a negative filter and vice-versa.
   * **Toggle** toggles a filter. By default, filters are inclusion filters and display in green. Only elements that match the filter are displayed. To change this to an exclusion filter, displaying only elements that do not match, toggle the filter. Exclusion filters display in red.
   * **Remove** removes the filter.

### Edit a Filter

The Edit filter option lets you manually update the filter and specify a label for it.

**Do these steps:**

1. Mouse over the filter that you want to edit and click the **pencil** **icon** \(Edit filter\): ![](../.gitbook/assets/7408052.png) The Edit filter dialog appears. ![](../.gitbook/assets/7408055.png)
2. Edit the filter by clicking **Edit Query DSL** and following the instructions to edit a filter.
3. Click **Save**.

### Manage a Filter

**Do these steps:**

1. Mouse over the filter that you want to manage, for example: ![](../.gitbook/assets/7408058.png)
2. Select any of the **action buttons** to manage a filter:
   * **Enable** enables a disabled filter.
   * **Disable** disables the filter without removing it. Diagonal stripes indicate that a filter is disabled.
   * **Pin** pins the filter. Pinned filters persist when you switch contexts. For example, you can pin a filter in one dashboard and it remains in place when you switch to another dashboard. A filter is based on a particular index field—if the indices being searched do not contain the field in a pinned filter, it has no effect.
   * **Unpin** disables a pin filter.
   * **Exclude matches** excludes items that match the specified field value.
   * **Remove** removes the filter.
   * **Edit filter** opens the Edit filter dialog.

