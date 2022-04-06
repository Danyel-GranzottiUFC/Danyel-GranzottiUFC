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
    public function getWebDeveloperPortifolio(): array
    {
        return [
           'url' => 'https://danyel-granzotti-portifolio.netlify.app/'         
        ];
    }
    public function getDailyKnowledge(): array
    {
        return [
            EmbeddedSystems::class,
            3D-Modeling::class,
            Javascript::class,
            React::class,
            Vue::class,
            HTML5::class, 
            CSS3::class, 
            Next.js::class,
            Bootstrap::class
        ];
    }
    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```

