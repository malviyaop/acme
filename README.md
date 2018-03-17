# acme
Acme Corp is a fictional company that has been selling insurance products for over 30 years. However, Acme hasn't kept up with technology and still sells its products manually - over the phone, in person, by mail, etc. 

This repository is going to track Acme's ambitions to transform itself into a digital power house. This will consist of the following [Projects](##Technologies):

* .NET Core monolithic backend
* iOS client app (Swift)
* Android client app (Kotlin)
* React web internal app

Acme sells Auto, Home, Appliances, Retirement, Health, and Consumer Electronics insurance products (Plan). But the initial plan is to digitize only its Appliances and Consumer Electronics products.

### Products

Acme's current Appliances Plan only covers the following items:

| Item         | Purshase Date | Purshase Price|
|--------------|---------------|---------------|
| Stove        | 1 year        | $0.00         |
| Refrigerator | 1 year        | $0.00         |
| Dishwasher   | 1 year        | $0.00         |
| Washer       | 1 year        | $0.00         |
| Dryer        | 1 year        | $0.00         |
| Microwave    | 1 year        | $0.00         |
| Blender      | 1 year        | $0.00         |
| Toaster      | 1 year        | $0.00         |

Acme's current Electronics Plan only covers the following items:

| Item         | Purshase Date | Purshase Price|
|--------------|---------------|---------------|
| TV           | 1 year        | $0.00         |
| Radio        | 1 year        | $0.00         |
| Computer     | 1 year        | $0.00         |
| Camera       | 1 year        | $0.00         |
| Smart Phone  | 1 year        | $0.00         |
| Tablet       | 1 year        | $0.00         |
| Printer      | 1 year        | $0.00         |
| Thermostat   | 1 year        | $0.00         |

> The reason these products were initially selected is their simple **price** structure

Selected Plans price structure:

| Plan         | Minimum Cost | Cost per Item |
|--------------|--------------|---------------|
| Appliances   | $11.99       | $3.99         |
| Electronics  | $9.99        | $1.99         |

`Minimum Cost` is the Plan cost regardless of how many items are added to the plan. For example, if the Applicance plan is chosen and one item is added, the total is **$15.98** - the Plans minimum $11.99 plus item $3.99.

After the Minimum Cost, the Plan increases as items added.

> The Minimum Cost is only applied once if devices from both plans are selected. For example, if a client adds a Stove (Appliances) and a Smartphone (Electronics) the total cost is the most expensive Minimum Cost plus the price of each item.

`Cost per Item` is simply the cost of adding an item to the Plan.


### Search
Pending....

### Cart
Pending....

### Account
Pending....

### Billing
Pending....

### Claims
Pending....

## Technologies

### Backend - .Net Core 2.0
The backend is developed in [.NET Core 2](https://github.com/dotnet/core) on a mac using [Visual Studio for Mac Community](https://www.visualstudio.com/vs/mac/) and [Visual Studio Code](https://code.visualstudio.com).

For persistene Entity Framework [EF Core 2.0.2](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/2.0.2) with [SQLite](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Sqlite) as the underlying database are used.

#### Architecture
Pending...

### Client App - iOS
Native [iOS](https://www.apple.com/ios/ios-11/) app develop in [Xcode](https://developer.apple.com/xcode/) using the [Swift](https://swift.org) Programming Language.

#### Design
Pending...

#### Architecture
Pending...

### Client App - Android
Native [Android](https://www.android.com) app develop in [Android Studio](https://developer.android.com/studio/index.html) using the [Kotlin](https://kotlinlang.org) Programming Language.

#### Design
Pending...

#### Architecture
Pending...

### Administrative App - React
A web app develop in [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) using the popular [React](https://reactjs.org) web-framework

#### Design
Pending...

#### Architecture
Pending...

## Who do I talk to?
Miguel Fermin via

[Email](mailto:mfermin@mafsoftware.com)

[LinkedIn](https://www.linkedin.com/in/miguel-fermin-94658544/)

[Twitter](https://twitter.com/mfermineet)



