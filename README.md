```php
namespace DanyelGranzotti;
class About extends Me
{
    public function getOccupation(): array
    {
        return [
           'company' => 'UFCQuixadá',
           'position' => 'ComputerEngineeringStudent'         
        ];
    }
    public function getDailyKnowledge(): array
    {
        return [
            EmbeddedSystems::class,
            ThreeDimensionalPrinting::class,
            Javascript::class,
            ReactNative::class,
            Aws::class,
        ];
    }
    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```

