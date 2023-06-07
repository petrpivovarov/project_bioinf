# project_bioinf
ARID2 это субъединица комплекса ремоделирования хроматина PBAF, которая сопровождает лиганд-зависимую активацию транскрипции ядерными рецепторами

В статье [1] устанавливается связь белка ARID2 с модификацией H3k27ac. Потеря ARID2 при меланоме приводит к нарушению сборки комплекса PBAF, при этом пики h3k27ac понижаются. 

Также связь наблюдается и в статье [2]. ARID2 связывался со всеми enhancer'ами с большим сигналом в на тех участках, где велико количество 
H3K27ac.

Экспрессируется больше всего в яичках, легких, коре больших полушарий головного мозга.

Размер гена небольшой, в структуре имеет один домен ARID, также есть небольшая белковая структура Zinc-Finger типа C2H2.

Гены позвоночных из таблицы оказались тем же геном ARID2, но в случае Zebrafish там другая изоформа меньшей длины, поэтому я решил посмотреть на дрозофилу. Ее ближайший протеин имеет код NP_610216.1, а название BAP170. Длина этого протеина равна 1688, у протеина соответствующего моему гену она равна 1835. Основная функция BAP170 такая же, как и у ARID2, он участвует в ремоделировании хроматина [3]. Для большей уверенности в том, что BAP170 и ARID2 - гены гомологи, я воспользовался принципом "Reciprocal best match", я поискал во всем протеоме человека гены схожие с BAP170, первым хитом оказался как раз таки ген ARID2, но другая его изоформа ARID2 isoform X1. Поэтому можно предположить, что гены BAP170 дрозофилы и ARID2 человека действительно гомологи

[1] Carcamo, Saul, et al. "Altered BAF occupancy and transcription factor dynamics in PBAF-deficient melanoma." Cell reports 39.1 (2022): 110637

[2] Raab, Jesse R., Samuel Resnick, and Terry Magnuson. "Genome-wide transcriptional regulation mediated by biochemically distinct SWI/SNF complexes." PLoS genetics 11.12 (2015): e1005748.

[3]Chalkley, G. E., Moshkin, Y. M., Langenberg, K., Bezstarosti, K., Blastyak, A., Gyurkovics, H., Demmers, J. A., & Verrijzer, C. P. (2008). The transcriptional coactivator SAYP is a trithorax group signature subunit of the PBAP chromatin remodeling complex. Molecular and cellular biology, 28(9), 2920–2929.

Таблица до логарифмирования evalue:

![image](https://github.com/petrpivovarov/project_bioinf/assets/115037034/c755cd6e-72ca-4a0d-8d2a-42e4bcc6af44)

Итоговая таблица:

![image](https://github.com/petrpivovarov/project_bioinf/assets/115037034/26f00bc1-eb45-4c04-a197-a34610b2b65e)

Тепловая карта:

![image](https://github.com/petrpivovarov/project_bioinf/assets/115037034/c78ee83f-fb5e-4432-ace9-4d4709d73700)

