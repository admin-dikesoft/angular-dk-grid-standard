
# DkGrid Standard Edition

**An Angular Data Grid for Angular Developers**

**DkGrid Standard Edition** is a component **engineered** and **built** using the **Angular Framework** and some **CDK behavior primitives** to display and manipulate tabular data. You can provide data from an array of **JSON** objects or a **REST API**. Nevertheless, you can define your **custom DataSource**.

DkGrid has ready-to-use features such as **filtering**, **editing**, **selection**, **sorting**, **paging**, **column grouping**, and **row grouping**, to mention a few. Apart from the key features, the DkGrid component is **highly customizable**. For instance, you can change the size of the column headers or the height of the content rows and customize many more properties.

The following image shows how our grid looks with some filters, row grouping, and edition enabled.

<a href="https://github.com/admin-dikesoft/angular-data-grid/blob/831b80a9b7aef3612899e9540e6312d71c6a5ea6/dike-grid-demo.png" target="_blank">
  <img src="https://github.com/admin-dikesoft/angular-data-grid/blob/831b80a9b7aef3612899e9540e6312d71c6a5ea6/dike-grid-demo.png" title="DkGrid Demo" style="max-width:100%;">
<a>

## Compatibility

### DkGrid and Angular versions

DkGrid doesn't follow Angular's versioning. Instead, we try to maintain compatibility with Angular majors for as long as possible, only breaking when we need to support a new major version.

| Angular | DkGrid |
| --------|--------|
| 14      | ^2.0   |
| 13      | ^1.0   |
| 12      | ^1.0   |

## License

DkGrid Standard Edition component is a commercial product and requires a paid license for use. Therefore, DkGrid Standard Edition is subject to the terms and conditions defined in [DkGrid Standard Edition EULA](https://www.dikesoft.com/legal/dk-grid/license-agreement).

You can purchase a license at [www.dikesoft.com/dk-grid](https://www.dikesoft.com/dk-grid).

## Key Features

* [Column definitions](https://docs.dikesoft.com/columns/column-definitions) &dash; To start using the DkGrid, you may define the columns that comprise your tabular data. There are four types of columns depending on the data they hold. Apart from column definitions, you can group columns with no limit on nesting groups.
* [Customization](https://docs.dikesoft.com/fundamentals/grid-structure) &dash; You can customize the height of the column headers, the pagination row, and the group panel. In addition, you can make the DkGrid shows a mat-elevation and the value of this elevation. You can also make vertical lines visible and customize many more properties.
* [Column Operations (resizing, moving, locking)](https://docs.dikesoft.com/columns/column-sizing) &dash; Once you have defined which columns will comprise your DkGrid instance, you can change their size or move them to any of the existing panels. Four panels are in each DkGrid instance: left, center, right, or group panel. In addition, you can freeze any column in any panel.
* [Cell Formatting](https://docs.dikesoft.com/columns/column-definitions) &dash; By default, the DkGrid shows every field value with predefined templates depending on the column types. Nevertheless, you can provide your custom templates for each defined column.
* [In-Memory DataSource](https://docs.dikesoft.com/fundamentals/datasource/in-memory-datasource) &dash; The DkGrid uses the In-Memory DataSource when you provide your data from a REST API or simply an array. 
* [Filtering](https://docs.dikesoft.com/filtering/column-filters) &dash; The easiest way to allow the user to filter rows is by displaying a dedicated filter row that shows a textbox for each visible column. Or any column could show a context menu where the user can type their values for each filter condition. You can tell the DkGrid which filter conditions to display and define each condition implementation.
* [Editing](https://docs.dikesoft.com/editing/row-edition) &dash; You can define which columns the user can edit. By default, the DkGrid offers templates for fields edition, but you can provide your custom templates using the well-known ng-template. Furthermore, the user can toggle the edition mode at runtime.
* [Sorting](https://docs.dikesoft.com/rows/row-sorting) &dash; The DkGrid allows the user to order the rows by any column. Just tell DkGrid which columns are sortable.
* [Paging](https://docs.dikesoft.com/rows/row-pagination) &dash; With paging implemented, the DkGrid will only load the number of rows you specify in the DkGrid\'s pageSize property. In addition, you can use paging when you provide your custom DataSource.
* [Selection](https://docs.dikesoft.com/rows/row-selection) &dash; The DkGrid allows the user to select one or more rows through a column of checkboxes. You can specify which rows are selectable, defining the criteria the rows must meet.
* [Theming](https://docs.dikesoft.com/fundamentals/theming) &dash; The DkGrid bases its theming process on the Angular Material\'s Theming System, allowing you to apply the same structure the Angular Material components use.

## Features included in the DkGrid Standard Edition

* [DataSource Decorators](https://docs.dikesoft.com/fundamentals/datasource/in-memory-datasource#datasource-decorators) &dash; Once you have provided your data, you can tell DkGrid how to manage your data before displaying it, defining a custom pipe of operations.
* [Custom DataSource](https://docs.dikesoft.com/fundamentals/datasource/custom-datasource) &dash; You can define a custom DataSource if you need to take more control over your data. Therefore, a Custom DataSource must extend from the abstract class DataSource.
* [Row Grouping](https://docs.dikesoft.com/rows/row-grouping) &dash; The DkGrid allows the users to group rows by a field by dragging and dropping the specific column in the group panel. Furthermore, row grouping is not limited to a single column, and the DkGrid will nest any number of groups and subgroups.

## Resources

[Getting Started with DkGrid](https://docs.dikesoft.com/getting-started/quick-start-tutorial)

[DkGrid product page](https://www.dikesoft.com/dk-grid)

[DkGrid product docs](https://docs.dikesoft.com/)

## Demos

You can visit our [complete demo](https://www.dikesoft.com/dk-grid-demo), which contains **22 columns**. Moreover, you can generate up to **100K** rows.

Furthermore, we have created one [live example](https://demos.dikesoft.com/dk-grid/getting-started) for each section in the [documentation](https://docs.dikesoft.com/).

## Support

For any issues you might encounter while working with the DkGrid component, please email to support@dikesoft.com

*Copyright © 2022 Dikesoft. All rights reserved.*
