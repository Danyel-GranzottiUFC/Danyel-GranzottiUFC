namespace DanyelGranzotti;

class About extends Me
{
    public function getOcupation(): array
    {
        return [
            'School' => [
                'university' => 'UFC - Quixadá',
                'position' => '1°S'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [

            Javascript::class,
            Vuejs::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
