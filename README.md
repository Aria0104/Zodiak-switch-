Console.WriteLine("Ваше имя");
string name = Convert.ToString(Console.ReadLine());
Console.WriteLine("Ваша фамилия");
string surname = Convert.ToString(Console.ReadLine());
Console.WriteLine("Дата рождения");
int date = Convert.ToInt32(Console.ReadLine());
Console.WriteLine("Месяц рождения");
int month = Convert.ToInt32(Console.ReadLine());

string zodiack = "";

    switch (month)
{

    case 1:
        if (date >= 1 && date <= 20)
        {zodiack = "Козерог"; }

        else if (date >= 21 && date <= 31)
        {zodiack = "Водолей"; }
        break;

    case 2:
        if (date >= 1 && date <= 18)
        {zodiack = " Водолей"; }

        else if (date >= 19 && date <= 28)
        {zodiack = "Рыбы"; }
        break;

    case 3:
        if (date >= 1 && date <= 20)
        { zodiack = " Рыбы"; }

        else if (date >= 21 && date <= 31)
        {zodiack = "Овен"; }
        break;

    case 4:
        if (date >= 1 && date <= 19)
        { zodiack = "Овен"; }

        else if (date >= 20 && date <= 30)
        {zodiack = "Телец"; }
        break;

    case 5:
        if (date >= 1 && date <= 20)
        {zodiack = "Телец"; }

        else if (date >= 21 && date <= 31)
        { zodiack = "Близнецы"; }
        break;

    case 6:
        if (date >= 1 && date <= 21)
        { zodiack = "Близнецы"; }

        else if (date >= 22 && date <= 30)
        { zodiack = "Рак"; }
        break;

    case 7:
        if (date >= 1 && date <= 22)
        { zodiack = "Рак"; }

        else if (date >= 23 && date <= 31)
        { zodiack = "Лев"; }
        break;

    case 8:
        if (date >= 1 && date <= 22)
        { zodiack = "Лев"; }

        else if (date >= 23 && date <= 31)
        { zodiack = "Дева"; }
        break;

    case 9:
        if (date >= 1 && date <= 22)
        { zodiack = "Дева"; }

        else if (date >= 23 && date <= 30)
        { zodiack = "Весы";}
        break;

    case 10:
        if (date >= 1 && date <= 23)
        { zodiack = "Весы"; }
        
        else if (date >= 24 && date <= 31)
        { zodiack = "Скорпион"; }
        break;

    case 11:
        if (date >= 1 && date <= 22)
        { zodiack = "Скорпион"; }

        else if (date >= 23 && date <= 30)
        { zodiack = "Стрелец"; }
        break;

    case 12:
        if (date >= 1 && date <= 21)
        { zodiack = "Стрелец"; }

        else if (date >= 22 && date <= 31)
        { zodiack = "Козерог"; }
        break;

    default:
        zodiack = "Неизвесен";
        break;

}

Console.WriteLine($"Ваше имя: {name}, Ваша фамилия {surname}, Ваш знак зодиака {zodiack}");
